---
layout:     post
title:      "VIM常用命令介绍"
subtitle:   "Make programming more efficient."
date:       2019-1-17 00:19:46
author:     "ZHANG jin"
header-img: "img/vim.jpeg"
tags:
- vim
---

<script type="text/javascript" async src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML"> </script>

*不少人在讲VIM堪称神器，所以那怎么能不去尝试一番呢。据说是需要背很多的命令，但挑战一下也是一件有趣的事嘛，就像曾经刚接触Markdown也觉得好奇怪，如今用起来也很是顺手。那就正好在这里做一个汇总，把常用的命令列出来，也可以当做是一个学习笔记。*

*第一步：**Esc**进入NORMAL模式。*

### 基本命令：

​	**:w**		保存

​	**:q**		退出

​	**:q!**		退出不保存

​	**:qa!**		强行关闭当前所有文档不保存

​	**:wq**		保存并退出

​	**x**		删除光标所在字符

​	**dd**		删除所在行

​	**p**		粘贴

​	**yy**		复制当前行

​	**i**		在当前光标前插入并进入**INSERT**模式

​	**a**		在当前光标后插入并进入**INSERT**模式

​	**o**		在当前行后插入新的一行

​	**O**		在当前行前插入新的一行

​	**hjkl**		光标控制：左 下 上 右

​	**0**		光标跳到当前行头

​	**$**		光标跳到当前行头

​	**^**		到本行第一个不是空格的光标位置

​	**g_**		到本行最后一个不是空格的光标位置

​	**u**		取消上一步操作

​	**Ctrl+r**	重复上一步操作

### 进阶命令：

