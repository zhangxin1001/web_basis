##创建分支 git branch (分支名)

##切换分支 git checkout (分支名)

##删除分支   git branch -d (分支名)

##获取当前分支下的文件  git pull origin (分支名)

##合并分支到master    git merge (分支名)

##本地仓库和远程仓库关联 git remote add origin <url>  

##将本地的master分支提交到远程的TS分支  git push origin master:TS

##获取远程仓库指定的分支数据   git clone  -b 分支名称  url

##暂存区与版本区保持一致    git reset HEAD <file>
  
##暂存区覆盖工作区的内容    git checkout <file>

##删除暂存区文件         git rm <file> --cached
 
##恢复版本区指定版本的内容到工作区  git reset --hard <version>
  
##查看引用版本号   git reflog

##git add . 和 git commit -m ""   可以合并为  git commit -a -m  ""

