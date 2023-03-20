## 1、基础功能

* 分支切换
```shell
git checkout <branch>
````
* 基于当前分支创建新分支并切换
```shell
git checkout -b <beanch>
```
* **基于远程分支创建新分支**
```shell
git checkout -b <branch> origin/<branch>
```
该命令相当于
```shell
git branch <branch> origin/<branch>
git checkout <branch>
```
* **基于远程分支的某个commitId创建新分支**
```shell
git checkout -b <new_branch> <commit_id>
```
该命令相当于以下两条命令
```shell
git branch <new_branch> <commit_id>
git checkout <new_branch>
```
## 2、扩展

* 修改文件
```shell
# 文件在工作区修改未提交至暂存区,使用该命令撤销修改
git checkout <file_name>

# 回退文件到某个commit状态
git checkout <commit_id> <file_name>
```
* 基于当前分支新建一个赤裸裸的分支，该分支无任何提交历史，但是内容不会丢失。（正常创建的分支，会继承之前分支的提交历史）
```shell
git checkout --orphan <new_branch>
```