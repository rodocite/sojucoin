What is Sojucoin?
----------------

Sojucoin is a cryptocurrency dedicated to my puppy, Soju. It's a fork of Litecoin.

![](https://github.com/rodocite/sojucoin/blob/master/soju.jpg)

Running a Node
----------------
```
docker pull rodocite/2bd33f4a1d0a
docker run rodocite/2bd33f4a1d0a
```

Mining
----------------
```
docker pull rodocite/2bd33f4a1d0a
docker run -it --entrypoint=/bin/bash rodocite/2bd33f4a1d0a -i
sojucoind &
sojucoin-cli generate 1
```
