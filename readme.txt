Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.
First Connecting ...
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；

关联后，使用命令git push -u origin master第一次推送master分支的所有内容；

此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；

要克隆一个仓库，首先必须知道仓库的地址，然后使用git clone命令克隆。
$ git clone git@github.com:allanwu96/gitskills.git