---
title: 文件上传下载
keywords: shenyu
description: 文件上传下载
---

## 说明

* 本文主要介绍 ShenYu 的文件上传下载的支持。

## 文件上传

* 默认限制文件大小为10M。
* 如果想修改，在启动服务的时候，使用`--file.size = 30`，为int 类型。
* 你之前怎么上传文件，还是怎么上传。

## 文件下载

* ShenYu 支持流的方式进行下载，你之前的接口怎么写的，还是怎么写，根本不需要变。