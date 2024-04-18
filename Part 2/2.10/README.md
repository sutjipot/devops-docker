After running
```shell
docker run -it --rm --network host networkstatic/nmap localhost
```
It shows
```shell
Starting Nmap 7.92 ( https://nmap.org ) at 2024-04-16 23:38 UTC
Nmap scan report for localhost (127.0.0.1)
Host is up (0.000012s latency).
Other addresses for localhost (not scanned): ::1
Not shown: 998 closed tcp ports (reset)
PORT    STATE    SERVICE
80/tcp  filtered http
111/tcp open     rpcbind

Nmap done: 1 IP address (1 host up) scanned in 1.51 seconds
```
 
