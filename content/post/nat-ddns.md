---
title: 如何内网穿透+闲置的电脑能干啥？做服务器啊
date: 2018-11-17 18:54:06
urlname: nat-ddns
categories: [网络]
tags: [内网穿透]
---

内网穿透，举个例子，我有个笔记本，然后闲置了，连上网了，可是远程怎么用，虽然可以使用teamviewer这种，可以作为一种工具。不过对于我来说不合适。

<!--more-->

需求：

Linux服务器：最后自己做个映射。

Windows这种：用teamviewer足够了，也可以做映射，比如做为自己的网站，内容都保存在自己的电脑上，也ok，好多都用树莓派啥的做服务器，也都行。

网盘：用群辉，google或者百度一搜一堆教程。

电脑重装成centos，需要远程访问，需要暴漏ip地址，但是外网的ip是活动的，因此需要使用第三方服务器，最快捷的就是使用花生壳，6块钱买个服务。

简单说一下步骤：

## 注册

按照网址http://service.oray.com/question/4287.html 注册，然后购买内网穿透，有一点就是映射列表添加的时候内网主机写

127.0.0.1

![](https://i.loli.net/2019/11/03/5bcO3GYe8vQt9RU.jpg)

自己远程ssh的时候，用户名密码记得写自己服务器的用户名，密码。
