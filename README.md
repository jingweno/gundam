Gundam
======

Gundam is the most destructive robot! It conquers the world with Go and [Sphero](http://www.gosphero.com/).

![](https://dl.dropboxusercontent.com/u/1079131/00_gundam.jpg)

```plain
$ go build
$ PORT=/dev/tty.Sphero-ORY-AMP-SPP ./gundam
2014/01/31 13:51:09 Initializing connections...
2014/01/31 13:51:09 Initializing connection  sphero ...
2014/01/31 13:51:09 Initializing devices...
2014/01/31 13:51:09 Initializing device  Gundam ...
2014/01/31 13:51:09 Starting connections...
2014/01/31 13:51:09 Starting connection sphero...
2014/01/31 13:51:09 Connecting to sphero on port /dev/tty.Sphero-ORY-AMP-SPP...
[martini] listening on host:port :3000
Starting connections...
Starting connection sphero...
Connecting to sphero on port /dev/tty.Sphero-ORY-AMP-SPP...
Starting devices...
Starting device sphero...
Device sphero started

$ curl -X POST localhost:3000/rgb/255,0,0
ok
```
