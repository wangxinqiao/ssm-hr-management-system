# ssm人事管理系统含项目报告

## 项目介绍
ssm人事管理系统。主要功能有：

用户管理：用户查询、添加用户；
部门管理：部门查询、添加部门；
职位管理：职位查询、添加职位；
员工管理：员工查询、添加员工；
公告管理：公告查询、添加公告；
下载中心：文档查询、上传文档；

## 环境需要
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。

2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；

## 技术栈
1. 后端：Spring SpringMVC MyBatis
2. 前端：ligerUI+jquery+metronic+jsp

## 使用说明
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中db.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/xxx 登录
5. 账户：admin  密码：123456

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183550_d884dbb1_9599873.jpeg "WechatIMG1944.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183652_fe9a7549_9599873.jpeg "WechatIMG1945.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183700_386a86d6_9599873.jpeg "WechatIMG1946.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183710_19a30f79_9599873.jpeg "WechatIMG1947.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183718_1d9a9d49_9599873.jpeg "WechatIMG1948.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183726_fd3ae724_9599873.jpeg "WechatIMG1949.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183735_c05c95e2_9599873.jpeg "WechatIMG1950.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183743_2537fcdd_9599873.jpeg "WechatIMG1951.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183755_09b1bed7_9599873.jpeg "WechatIMG1952.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/183803_90d1f0ad_9599873.jpeg "WX20210713-140213@2x.jpg")


