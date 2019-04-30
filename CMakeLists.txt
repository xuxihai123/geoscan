cmake_minimum_required(VERSION 3.14)
project(geoscan)

set(CMAKE_CXX_STANDARD 98)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -pthread")

add_executable(geoscan geoscan.c)