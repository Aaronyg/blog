---
<<<<<<< HEAD
title: git guide
date: 2018-03-17 11:22:22
tags: IT•git
---

### 常用命令

````
1. git init
2. git status
3. git add *
4. git commit -m "use git command"
5. git checkout -- file  #撤销修改
6. git remote add origin git@github.com:docker_user/blockchain_guide.git #增加远程仓库
7. git push origin master #第一次用git push -u origin master
8. git clone git@github.com:docker_user/blockchain_guide.git
9. git branch dev #创建分支dev
10. git checkout dev 切换到分支dev
11. git checkout -b dev #-b参数表示创建并切换到分支，相当于两句：git branch dev , git checkout dev
12. git branch #查看当前分支
13. git merge dev #合并分支dev
14. git branch -d dev #删除分支dev
15. git log --graph #看到分支合并图
16. git branch -D <name> #强行删除
17. git remote #查看远程库信息，详情git remote -v
18. git checkout -b dev origin/dev #创建远程origin的dev分支到本地
19. git pull  #把最新的提交从origin/dev抓下来
20. git diff HEAD -- readme.txt #可以查看工作区和版本库里面最新版本的区别
21. git remote rm origin ##删除远程库
22. git pull --rebase origin master

````
### 例子

````
# 在 GitHub 上 fork 到自己的仓库，然后 clone到本地，并设置用户信息
$ git clone git@github.com:docker_user/blockchain_guide.git
$ cd blockchain_guide
$ git config user.name "yourname"
$ git config user.email "your email"
# 更新内容后提交，并推送到自己的仓库。

$ git commit -am "fix"
$ git push

# 最后，在 GitHub 网站上提交 pull request 即可。
# 另外，建议定期使用项目仓库内容更新自己仓库内容。
$ git remote add upstream https://github.com/yeasy/blockchain_guide
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
````
=======
title: git
date: 2018-03-17 11:22:22
tags: tools
---
>>>>>>> 812ef10077b1951226297d0bc0831b5cd59e1ee3
