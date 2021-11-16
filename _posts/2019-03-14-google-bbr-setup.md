---
layout: post
title:  开启 Google BBR
date: 2019-03-14 00:01:00 +0000
tags:
  unix
---

In Debian 9

``` sh
echo "net.core.default_qdisc=fq" >> /etc/sysctl.conf
echo "net.ipv4.tcp_congestion_control=bbr" >> /etc/sysctl.conf
sysctl -p
lsmod | grep bbr
```
