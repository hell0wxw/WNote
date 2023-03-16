

## 1. git reset --soft  
soft 只会撤销本次提交，对于工作区和暂存区不做修改

## 2. git reset --mixed
--mixed为默认参数
mixed会撤销本次提交以及暂存区内容，工作区不做修改

## 3. git reset --hard
hard会撤销本次提交、暂存区、工作区内容，执行该命令后，修改内容将丢失

## 4. 版本记录操作
使用 git reflog 查看版本操作记录
之后使用git reset --hard 恢复版本

> HEAD@{2} means “where HEAD used to be two moves ago”, master@{one.week.ago}means “where master used to point to one week ago in this local repository”  

HEAD@{2}表示HEAD指针在两次移动之前的情况；而 master@{one.week.ago}表示master在本地仓库一周之前的情况。