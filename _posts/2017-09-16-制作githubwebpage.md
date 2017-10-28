---
layout: default
title: make-GitHubWebpage
---

[jekyll中文教程](http://jekyllcn.com/docs/troubleshooting/)
# 几个坑
## 设置域名关联gitub.webpage
域名里的主机名不理解是什么，实际上就是对于同一个ip上多个网站，根据主机名区分，如果直接主页的话，可以用www,比如像我的博客，就可以设置为blog。这时候在CANME里就需要用blog.chenyuzhao.xyz了。[这里说的比较清楚](http://note.youdao.com/)
## 设置背景图片链接
之前不知道，按照_post,_layout这样命名了存储图片的文件夹，然后一直报错说找不到图片路径，实际上，对于webpage会对_开头的文件夹进行特殊处理，所有就找不到了，将文件夹名字前面的下划线去掉就ok了。
