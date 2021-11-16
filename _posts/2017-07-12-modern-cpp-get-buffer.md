---
layout: post
title:  Modern C++ get buffer
date: 2017-07-12 00:01:00 +0000
tags:
  cpp
---
``` cpp
std::unique_ptr<char[]> buffer(new char[n]);
buffer.get()
```
