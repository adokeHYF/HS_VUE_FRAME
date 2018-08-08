1.git branch -a: 查看所有的git 分支

2.github上已经有master分支 和dev分支
  在本地:

  git checkout -b dev 新建并切换到本地dev分支

  git pull origin dev 本地分支与远程分支相关联
  
3.在本地新建分支并推送到远程

  git checkout -b test

  git push origin test   这样远程仓库中也就创建了一个test分支
  
4.删除远程分支
  git push origin --delete dev
  
5.删除本地分支
  git branch -d dev