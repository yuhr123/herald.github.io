---
title: 服务器流量监控工具 iptraf 和 ipftop
layout: post
date: '2017-08-11 14:09:45'
---

### iftop 实时流量监控

安装
```
~$ sudo apt install iftop
```

打开监控界面
```
~$ sudo iftop
```

显示某个网卡的流量状态
```
~$ sudo iftop -i enp3s0
```

### iptraf

安装
```
~$ sudo apt install iptraf
```

打开监控界面
```
~$ sudo iptraf-ng
```

### nload

能够分别统计 incoming 和 outgoing 流量，实时速度、平均速度、最大最小以及总流量。

#### 相关链接

* [iftop](http://www.ex-parrot.com/pdw/iftop/)
* [iptraf](http://iptraf.seul.org/)