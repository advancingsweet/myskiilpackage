[TOC]

# Git 基本使用



## 1.Git常用指令

![img](https://img-blog.csdnimg.cn/direct/fe1269fd0e6149a0adfabf784050b0f6.png)



## 2.Git安装、Git与Github绑定

1. [Git注册、登录和使用方法_git登录](https://blog.csdn.net/2401_87288638/article/details/142436425?spm=1001.2101.3001.6650.3&utm_medium=distribute.pc_relevant.none-task-blog-2~default~YuanLiJiHua~Position-3-142436425-blog-90055273.235^v43^control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2~default~YuanLiJiHua~Position-3-142436425-blog-90055273.235^v43^control&utm_relevant_index=6)



## 3.本地文档上传

1. [用git上传项目到GitHub](https://zhuanlan.zhihu.com/p/193140870)

```C++ 
git init //把这个目录变成Git可以管理的仓库
　　git add README.md //文件添加到仓库
　　git add . //不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 
　　git commit -m "first commit" //把文件提交到仓库
　　git remote add origin git@github.com:wangjiax9/practice.git //关联远程仓库
　　git push -u origin master //把本地库的所有内容推送到远程库上
```



**最最最关键的一步！！！指定上传仓库的位置（**

```C++
git remote add origin git@github.com:wangjiax9/practice.git //关联远程仓库
```





## 4.官方文档

![QQ_1732115379285](C:/Users/HONGWE~1/AppData/Local/Temp/QQ_1732115379285.png)

### create a new repository on the command line

```
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/advancingsweet/test.git
git push -u origin main
```



### push an existing repository from the command line

```
git remote add origin https://github.com/advancingsweet/test.git
git branch -M main
git push -u origin main
```

