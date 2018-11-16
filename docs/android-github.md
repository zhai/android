---
layout: page
title:  如何在Github上面贡献代码
description: 
date:   2018-11-11 15:03:25
categories: original
---
## Android入门知识指南

[返回](./)


####2. 切换分支，合并代码，同步源代码，提交代码

1.      fork
1.      git clone my.git
1.      git remote add upstream  his.git    //指向原始git
1.  是否切换到其他分支例如dev_remote，如果是进入以下操作
1.      git checkout origin/dev_remote  拉下分支
1.      git checkout -b dev_remote  
1.  修改代码
1.      git add -A
1.      git commit -a -m "添加的内容"
1.  拉取源库的更新并合并到本地
1.      git fetch upstream
1.      git merge upstream/dev_remote  合并
1.      git push origin dev_remote
1.  去github网站上去处理 pull request

 