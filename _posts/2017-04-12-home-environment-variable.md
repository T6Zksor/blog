---
layout: post
title:  重装系统后记得设置HOME环境变量
date: 2017-04-12 00:01:00 +0000
tags:
  windows
  misc
---

当计算机在 domain 中时，`$HOMEPATH` `$HOMEDRIVE` 默认会从 domain 获得，设置一个 `$HOME` 避免 git 找不到默认 .gitcinfig
