# git

打开：屏幕右键→Git Bash Here

配置用户名：git config --global user.name guowudi

配置邮箱： git config --global user.email gwd@123.com（邮箱不一定要真是存在的邮箱）

用git实现代码管理的过程：

1、如果从github上下载源码，可以用git clone

命令：git clone 某个项目的github连接

![8](https://frankgwd.oss-cn-hangzhou.aliyuncs.com/202208121401157.png)

2、打开自己的项目文件myproject，右键→git bash here→输入命令：git init

在myproject文件夹中会新增一个.git的文件夹（默认隐藏，需查看，√隐藏的项目才能看到）

![6](https://frankgwd.oss-cn-hangzhou.aliyuncs.com/202208120746648.png)

myproject文件夹中除.git以外的为工作区，在工作区中新建项目文件main.py

提交文件：

1、git add .	把mypeoject文件夹中除.git以外的文件和文件夹设为准备提交状态（暂存区）。【注意有个点 .】

2、git commit -m "这次提交的备注"	git会把源代码以数据库的形式保持在仓库中

![image-20220812075308410](https://frankgwd.oss-cn-hangzhou.aliyuncs.com/202208120753443.png)

3、git log 	查看提交的记录，包括作者，时间，备注

![7](https://frankgwd.oss-cn-hangzhou.aliyuncs.com/202208120756366.png)

4、git checkout HEAD manage.doc	从最后一次提交的文件里把manage.doc复制到工作区（会覆盖）

![image-20220812075927837](https://frankgwd.oss-cn-hangzhou.aliyuncs.com/202208120759863.png)

5、如果只要提交一个文件

git add manage.doc

git commit -m "功能2已完成"

git log

![image-20220812080356645](https://frankgwd.oss-cn-hangzhou.aliyuncs.com/202208120803673.png)

## 1.1 怎么找开源项目

github.com/trending

github.com/521xueweihan/HelloGithub

github.com/ruanyf/weekly

www.zhihu.com/column/mm-fe





## 1.2特殊查找资源小技巧

常用前缀后缀

找百科大全：awesome xxx

找例子：xxx sample

找空项目架子：xxx starter / xxx bolierplate

找教程：xxx tutorial