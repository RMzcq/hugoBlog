---
title: 解决google driver 开了代理(ss)之后也报错的问题
date: 2018-10-19 17:51:33
urlname: googleDriver problem1
categories: [工具]
tags: [google driver,ss]
---

问题困扰了很久，但是也找不到解决版本，后来使用关键字搜索到了。使用命令行的方式不建议，一是维护麻烦，而是不太懂。。。

<!--more-->

![](https://i.loli.net/2019/11/03/oWvEU7ey1nQRVXN.jpg)

自己的ss-ng默认开启了http和socket啊，但是不行，据说google drive 无法识别http proxy以外的proxy

## 下载 proxifier

有码的，这个可以自己找

## 需要在隐私中允许一下

## 添加 proxies

我的是ss-ng，因此添加 

![](https://i.loli.net/2019/11/03/dXI9xe7gmpMfkGq.jpg)

然后规则就有了，这个时候driver就可以用了，不过这个时候mac的所有应用请求都走的这个，得更改一下。

删掉其他的配置，没有用，也不用下载github的配置，因为最终还得走ss代理。下图中的各个项不明白的可以问我，比较简单就没介绍。按图配置就ok了。

![](https://i.loli.net/2019/11/03/zkvfsraYx93XqK6.jpg)

参考说是打上这个勾勾，可以防止dns污染。

![](https://i.loli.net/2019/11/03/Fd4qAcVp125QMNX.jpg)

别的就没有了，很简单。

## 两个不错参考的网址

链接都失效了，只能先放着

* http://blog.batesma.com/20170811-google-drive-proxy-solved/
* https://www.jianshu.com/p/91a7c17f4a0e


