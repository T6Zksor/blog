---
layout: post
title:  WriteFile API 第四个参数不能为 NULL
date: 2017-06-22 00:01:00 +0000
tags:
  windows
---

WriteFile API 在 win7 下第四个参数 byteswritten 不能和第五个参数同时为空，否则会有 exception。win10 下没有 exception。
