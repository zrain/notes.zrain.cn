---
title: Hexo source 目录下 README.md 文件处理
date: 2019-01-30 10:55:06
tags:
 - Hexo
---

有朋友遇到这样的问题：

Hexo 我们在 source 目录下放置了一个 README.md 文件，用于 github。

但是编译后发现 README.md 被编译成 README.html 文件。

接下来分享给大家最简单的解决办法

1. 打开跟目录下的 _config.yml 文件
2. 搜索 skip_render: 如果没有，则手动添加
3. skip_render: README.md
4. 保存，解决

或参考 hexo github 的相关 issues [[HEXO/ISSUES/1146](https://github.com/hexojs/hexo/issues/1146)]