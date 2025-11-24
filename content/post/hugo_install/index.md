---
title: "Hugo_install"
description: 
date: 2025-11-24T22:40:45+08:00
image: 
math: 
license: 
hidden: false
comments: true
draft: true
---

```bash
# 查看帮助
hugo -h

### hugo服务本地启动
# 1. 新建项目
# 2. 进入项目目录
# 3. 本地启动项目
# PS: 显示 Page Not Found 是正常的
hugo server -D


### stack主题安装
# 1. 下载文件, 解压到项目的 themes 目录, 解压后的名称不能带版本号
# 2. 复制 content目录 | .gitignore | hugo.yaml到项目目录, 并删除 content/post/*
# 3. 创建一个新文件

hugo new content post/hugo_install/index.md
```
