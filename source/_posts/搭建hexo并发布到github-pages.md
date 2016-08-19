---
title: Mac环境下搭建hexo并发布到Github Pages
date: 2016-08-14 21:39:16
comments: true
categories: 技术
tags: hexo 
---

首先，最好切换到root用户,否则每次都要sudu，特别麻烦。

```
$ sudo -i

```
### 安装开发依赖环境git和node.js

这两个软件的安装都比较容易。其中mac的话，最好安装Xcode，集成git，能少爬一点坑。

安装好git和node.js后就可以安装hexo了
	
进入到hexo的[官网文档页面](https://hexo.io/docs/)，按照文档说明一步一步来。

### 安装hexo

```
$ npm install -g hexo-cli

```
安装博客到folder这个目录,如果不跟这个目录的话，就是默认到当前目录
```
$ hexo init <folder>
$ cd <folder>
$ npm install
```

到这里你就可以运行

```
hexo server
```
来启动本地hexo服务了。在浏览器里输入[http://localhost:4000](http://localhost:4000)就能看到hellow world这篇文章了。

最后，介绍我现在用的这个我自己非常喜欢的主题：[大道至简](https://www.haomwei.com/technology/maupassant-hexo.html)

