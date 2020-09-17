###	1. 项目介绍

本项目是一个OA办公自动化系统，使用Maven进行项目管理，基于Springboot框架开发的项目，MySQL底层数据库，前端采用Freemarker模板引擎，Bootstrap作为前端UI框架，集成了jpa、mybatis等框架。

### 2. 项目地址

该项目转自: https://gitee.com/aaluoxiang/oa_system

### 3. 框架介绍
#### 前端

| 技术      |    名称| 版本|	官网|
| :--------: | :--------:| :--: |:--:|
| freemarker|模板引擎|springboot1.5.6.RELEASE集成版本|https://freemarker.apache.org/|
| Bootstrap|前端UI框架|3.3.7|http://www.bootcss.com/|
| Jquery|快速的JavaScript框架|1.11.3|https://jquery.com/|
|kindeditor|HTML可视化编辑器|4.1.10|http://kindeditor.net|
|My97 DatePicker|时间选择器|4.8 Beta4|http://www.my97.net/|

#### 后端

| 技术 | 名称 | 版本 | 官网 |
| :--------: | :--------:|:---:|:------:|
|SpringBoot|SpringBoot框架|1.5.6.RELEASE|https://spring.io/projects/spring-boot|
|JPA|spring-data-jpa|1.5.6.RELEASE|https://projects.spring.io/spring-data-jpa|
|Mybatis|Mybatis框架|1.3.0|http://www.mybatis.org/mybatis-3|
|fastjson|json解析包|1.2.36|https://github.com/alibaba/fastjson|
|pagehelper|Mybatis分页插件|1.0.0|https://pagehelper.github.io|

### 4. 部署流程

	1.下载项目、把oasys.sql导入本地数据库
	2. 修改application.properties
	3. 修改数据源，oasys——>自己本地的库名，用户名和密码修改成自己的
	4. 修改相关路径，配置图片路径、文件路径、附件路径。
	5. OasysApplication.java中的main方法运行，控制台没有报错信息，数据启动时间多久即运行成功
	6. 在浏览器中输入localhost:8088/logins


###  5. 项目演示
![演示4.gif](https://i.loli.net/2018/09/26/5bab4565b121e.gif)
![演示3.gif](https://images.gitee.com/uploads/images/2019/0927/141251_4ef0327c_1277461.gif)

![主页面.png](https://images.gitee.com/uploads/images/2019/0927/141250_2286d104_1277461.png)
![登陆页面.png](https://images.gitee.com/uploads/images/2019/0927/141250_f5277aa8_1277461.png)
![文件管理.png](https://images.gitee.com/uploads/images/2019/0927/141250_491ce25d_1277461.png)
![讨论区.png](https://images.gitee.com/uploads/images/2019/0927/141251_d4992cd4_1277461.png)
![新建流程.png](https://images.gitee.com/uploads/images/2019/0927/141251_c7d89853_1277461.png)
![通讯录.png](https://images.gitee.com/uploads/images/2019/0927/141251_bcf9cbda_1277461.png)