# git.instructions
#  git 常用命令

### 分支操作  branch

	#####  1 创建分支

​	git  branch  分支名字

​		*主分支必须有一次提交 才能创建分支

##### 2 查看分支 

​	git branch

​		*master 主分支 默认的

##### 3 切换分支

​	git checkout  分支名称

​		 *会复制主分支

​		切换之后   只有提交分支的内容之后（提交到代码仓库） 
​                才能进行分支的切换

##### 4 提交分支

​	git push origin 分支名

##### 5合并分支

​         git merge

​		*在主分支的角度（回到主分支） 将子分支合并到主分支

##### 6删除分支

​	git branch -d  分支名
   		*分支未被合并 默认情况不允许删除

​		 git branch - D 分支名 

​		强制删除

​		空分支 未进行任何操作 可以进行删除 
​		但也需要在主分支（或其他分支）上进行操作

##### 7删除远程仓库的分支

​	git push origin  :远程分支名

​		*意思是将本地空分支推送到远程分支，相当于删除远程分支

​	

​	





































