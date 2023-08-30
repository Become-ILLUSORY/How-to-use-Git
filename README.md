# How-to-use-Git
You can study Git by it.
# 1.初始化仓库：git  init
# 2.git add -A   （将工作区的文件放到暂存区）
# 3.git commit -m  "提交信息（first commit）"  （将暂存区文件放到远程仓库）
	工作区————暂存区————远程仓库
# 4.git log --stat   查看提交的历史
# 5.git checkout "filename"  （撤销在工作区的更改）
# 6.git reset HEAD^  （撤销提交到远程仓库后的更改）
# 7.git checkout -b <branchname>  （以当前分支为基础新建分支）
# 8.git branch （列举所有分支）
# 9.git checkout <branchname>  (切换到指定分支)
# 10.git branch -D <branchname>  (删除指定分支)
# 11.git merge <branchname>   (合并分支)
# 12.git merge --abort  (放弃本次合并)    
# 13.git remote add origin https://xxxxxxxxxx.git  (将https://xxxxx.git作为远端仓库添加到本地git中)
# 14.git branch -m main  （将本地的master改为main —详见美国人权运动）
# 15.git push -u origin main (将本地仓库推送到远程仓库)
# 16.git push (推送当前分支的最新的提交到远程)
# 17.git pull (拉取远程分支最新的提交到本地)
