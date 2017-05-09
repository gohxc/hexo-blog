---
title: 使用hexo搭建博客
date: 2017-05-05 18:49:26
tags: hexo nodejs
---
# 前言
为什么我会想要搭建一个博客呢，可能我想留下点什么吧。作为一个工作快10年了的码农，
觉得有点虚度光阴，一个偶然的机会看到了hexo的静态博客。就在前一周开始学习搭建自己的博客了。  
nodejs也学了点入门吧，我把hexo博客搭建过程记录一下。

# Hexo简介
Hexo是一个基于Node.js的静态博客程序。
官方网址：[点击到hexo官网](https://hexo.io/) 或者 `https://hexo.io/`.
快速、简洁且高效的博客框架 [官方中文说明](https://hexo.io/zh-cn/docs/index.html)
# Hexo安装
这里安装最新版 hexo: 3.3.5 hexo-cli: 1.0.2 
1. 需要安装Nodejs环境 [点击 Node.js](https://nodejs.org/en/ "点击到官网下载") 下载最新的即可。
2. 安装Git环境 [点击 git](https://git-scm.com/ "点击到官网下载") 下载最新的即可。
3. windows系统应该很简单安装nodejs和git，下载以后傻瓜式next就可以了。
4. npm命令会和nodejs一起安装好，一般我们会弄个镜像 打开git bash 一般右键就会有
```
安装淘宝镜像
npm install -g cnpm --registry=https://registry.npm.taobao.org
以后可以使用cnpm代替npm
```
或者
指定淘宝镜像 npm config set registry https://registry.npm.taobao.org 
5.
$ npm install -g hexo-cli
这个命令需要管理员权限，windows下按窗口键或者点击开始菜单 输入git
![](http://i4.buimg.com/519918/2c41b2faa8d669fa.png)
