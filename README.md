### geoscan
geoscan from http://www.matveev.se/cpp/portscaner.htm


### usage

Usage: ./geoscan < hostname > < protocol > < portlow > < porthigh >

```sh
[toor@door geoscan]$ ./geoscan 127.0.0.1 tcp 1 65535
Scanning host=127.0.0.1, protocol=tcp, ports: 1 -> 65535
port 111: sunrpc
port 1080: socks
scan finished.


```

```sh
[root@door geoscan]# ./geoscan 192.168.2.1 udp 1 4000
Scanning host=192.168.2.1, protocol=udp, ports: 1 -> 4000
port 53: domain
port 67: bootps
port 68: bootpc
port 1701: l2tp
port 1900: ssdp
port 1901: fjicl-tep-a
scan finished.

```