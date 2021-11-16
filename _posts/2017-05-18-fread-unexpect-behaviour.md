---
layout: post
title:  fread 的坑
date: 2017-05-18 00:01:00 +0000
tags:
  cpp
  windows
---

用 text 模式打开 file pointer 后调用 fread 读取，实际读出的长度并不一定等于文件长度，因为在 Windows 下 text 模式把 `\r\n` 转成了 `\n`，少了1 byte
