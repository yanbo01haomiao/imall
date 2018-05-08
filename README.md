**Imall_learning** _使用Maven管理的SSM简单的商城项目_

05-08 问题：
- 数据库初始化完成；
- 使用IDEA创建空项目-并且配置好resources文件夹；
- 配置好Tomcat；
- 配置IDEA的Git终端：点击terminal的时候都会弹出git bash的窗口，设置的git安装目录下的bash，试改成bin目录下的启动文件即可。

05-08:创建V1.0分支，将从分支开发，之后整合到master。顺便熟悉git操作。

git push 出现Everything up-to-date的错误，是由于没有执行如下代码：

    git add .
	git commit -m 'V1.0 for practice'
	git push -u origin v1.0



