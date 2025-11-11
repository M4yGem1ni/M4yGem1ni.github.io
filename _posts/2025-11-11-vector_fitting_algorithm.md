---
layout: post
title: "关于vector fitting算法的一些思考"
date:   2025-11-11
tags: [algo]
comments: true
author: M4yGem1ni
---

> 正在施工中！

<!-- more -->

## 开始
Vector Fitting算法算是我接触的第一个算法了，也是我第一次使用`纸笔`和`numpy`推导实现的。
这个算法我学到了很多，在原先的`sckit-rk`库的基础上进一步完善，成就感满满。

## 引入
对于一个系统，当具有如下一些性质的时候，可以使用vector fitting算法进行拟合。

1. 拟合的系统必须是无源的
    对于一个多端口网络，从系统的1端口输入信号`sig1`