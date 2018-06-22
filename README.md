# dst-server
Host a `Don't Starve Together` dedicated server based on this [repo](https://github.com/dst-academy/docker-dontstarvetogether) using docker.

## Setup
```sh
iptables -I INPUT 7 -p udp --sport 10999 --dport 1025:65355 -j ACCEPT
```
