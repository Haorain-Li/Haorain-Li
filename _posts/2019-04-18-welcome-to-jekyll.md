---
title: "How to use git?"
date: 2019-04-18T15:34:30-04:00 ​	
categories:
  - blog
tags:
  - git
  - repository
---



```git
🔧 初始配置
$ git config --global user.name "xxxxx"

$ git config --global user.email "xxxxx"

$ ssh-keygen -t rsa -C “xxx”

📂 仓库初始化与基础操作
first time 
$ git init

$ git add .

$ git commit -m "commit"

🔗 连接远程仓库与推送
$ git remote add origin xxxx.xxxx

$ git push -u origin master

$ git push -u origin master -f

$ git branch -M main
```