



















git pull --rebase origin master
      Git中的分支，其实本质上仅仅是个指向commit 对象的可变指针。Git会使用master 作为分支的默认名字。在若干次提交后，你其实已经有了一个指向最后一次提交对象的master 分支，它在每次提交的时候都会自动向前移动。

         创建一个新的分支，即创建一个新的分支指针。比如创建一个testing分支，可以使用git branch命令：

## $ git branch testing

HEAD特别指针，在Git中，它是一个指向你正在工作中的本地分支的指针。运行git branch 命令，仅仅是建立了一个新的分支，但不会自动切换到这个分支中去。要切换到其它分支，可以执行git checkout命令：

## $ git checkout testing

这样HEAD就指向了testing分支。每次提交后HEAD随着分支一起向前移动。

## $ git checkout -b testing 

相当于：

## $ git branch testing

## $ git checkout testing

两条命令。
分支合并：用git merge命令来进行合并，

## $ git merge testing

 删除一个分支：

## $ git branch -d testing

格式化时间的你npm

## moment

## nrm 切换成淘宝镜像

## nrm use taobao

## 查看所有的镜像源

> npm ls

md文档转换为html页面

## npm i -g i5ting_toc

>   

i5ting_toc -f 要转换的md文件路径 -o

![](genfile.assets/2023-04-18_103445.png)



![](2023-04-18_110209.png)
