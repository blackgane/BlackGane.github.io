---
title: 利用Hexo + GitHub搭建个人博客
date: 2019-08-15 12:15:14
categories: 博客搭建
tags: Hexo
---

> 个人一直想搭建博客，最初是想自己搭建前台和后台所有内容，花费时间会比较长。（后续还是完成它）
无意在B站中看到UP主CodeSheep分享的Hexo搭建，一次成功，下面是搭建过程及遇到的问题。
<!--more-->

## 环境准备
1. Windows 10
2. Node.JS 10.16.2 LTS [Download](https://nodejs.org/en/)
3. Git 2.22.0  [Download](https://git-scm.com)

## 环境搭建
1. 先安装NodeJS，安装后打开命令行输入**npm -v**来测试是否成功安装。
```
$ npm -v
6.9.0
# 国内下载NPM模块速度慢，可以切换成淘宝NPM镜像加快下载速度。
$ npm install -g cnpm --registry=https://registry.npm.taobao.org
# 以后可以统一使用cnpm来安装了
$ cnpm install -g <Module Name>
```

2. 安装Git默认安装即可。
3. 安装Hexo
```
$ cnpm install -g hexo-cli
```

## 部署Hexo
1. 创建博客文件夹，右键空白处点击**Git Bash Here**
2. 在Bash里输入命令
```
$ hexo init # hexo 初始化
$ hexo s # hexo运行 （hexo server）
```
3. 打开浏览器，在地址栏输入**http://localhost:4000/** 即可访问博客啦。

未完待续...



