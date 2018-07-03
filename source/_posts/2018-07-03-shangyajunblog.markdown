---
layout: post
title: "octopress"
date: 2018-07-03 15:11:11 +0800
comments: true
categories: ['python','ruby','octopress']
---

#初识octopress

##1.	Octopress的基础知识
###1.1Octopress是什么？
- Octopress是一个基于Jekyll的静态的博客站点生成系统，它很大程度上简化了Jekyll的搭建博客的过程
### 为什么要使用Octopress？
### 我们说一下WordPress的缺点
- 我们得买主机（空间）、域名
- OverFeatured
- `动态网站`下载速度慢
- 过渡的`依赖数据库`
- 可控性差
- 容错性差
- 迁移成本高
- `网页编辑器写博客`耗费时间多
###Octopress优点
- 命令行操作
- 存文本写博客
- 定制性高
- 纯静态页面
- 版本化管理
- 迁移成本低
- 简介的Ruby框架
- markdown语法
##2.	Octopress的目录结构
- 主题插件等->自定义博客
- source->存放程序、博客源码（rake generate后生成public静态网页）
- public->存放生成的静态网站
##3.	Octopress的使用流程
- 搭建环境
- 纯文本书写博客
- 生成静态网页
- 本地预览
- 部署github