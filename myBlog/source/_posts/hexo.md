---
title: hexo + github page 搭建个人博客
date: 2018-03-13 11:22:22
<<<<<<< HEAD
tags: IT•hexo
---

### 安装node.js
下载并安装：[node.js](https://nodejs.org/en/) 

### 安装 git
下载并安装：[git](https://git-scm.com/) 

### 安装hexo
=======
tags: tools
---

## 安装node.js
下载并安装：[node.js](https://nodejs.org/en/) 

## 安装 git
下载并安装：[git](https://git-scm.com/) 

## 安装hexo
>>>>>>> 812ef10077b1951226297d0bc0831b5cd59e1ee3
````
npm install hexo-cli -g   #安装hexo   
npm install hexo-deployer-git --save #部署到github page

hexo init #初始化配置

hexo g  #生成静态页面
hexo s  #本地浏览器的localhost:4000 预览博文效果

hexo g -d  #发布到github上
````

<<<<<<< HEAD
### 设置hexo主题
=======
## 设置hexo主题
>>>>>>> 812ef10077b1951226297d0bc0831b5cd59e1ee3
````
$ hexo clean
$ git clone https://github.com/LouisBarranqueiro/hexo-theme-tranquilpeak.git themes/tranquilp
````