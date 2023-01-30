# git
git可以理解为是一个工具，这个工具帮助我们管理代码，Git是目前世界上最先进的分布式版本控制系统，他是安装到电脑上的一个命令行工具

# 使用git
使用git的第一步就是新建一个git仓库，一个git仓库可以理解为是一个目录，每一个目录都可以当成仓库使用，每一个仓库中又有很多文件和目录
1、初始化一个仓库：git init


# git常用命令
git config --global user.name "Your Name"
git config --global user.email "email@example.com"

git init
git status  查看当前工作区是否有修改
git diff <file> 查看修改的内容

git add <file>  将修改的文件添加到暂存区
git commit -m '描述' 将暂存区的修改添加到当前分支

git log 查看提交记录
git log --pretty=oneline

git reset --hard HEAD^  退回到上一个版本
git reset --hard HEAD^^  退回到上上一个版本
git reset --hard commitId  退回到指定版本

git checkout -- <file>  放弃当前工作区的修改，仅限于没有被add的文件

git remote -v 查看远程仓库的关联地址
git remote add origin <地址> 管理远程仓库
git push origin <master> 提交本地的修改到远程仓库
git pull origin <master> 更新远程仓库的修改到本地仓库
git clone <地址> 克隆一个远程仓库到本地


撒嗲世杰活动啦可是打开就好啦老师就看大龙卡就是大家快来撒娇哭了那是大伯即可撒的搬家看了春生全喂入；哦打开了那份v