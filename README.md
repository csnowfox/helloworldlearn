# 开发人员入门练习

** 适用于JAVA后台和前端开发岗位实习生基础技能储备**

## 1. 目标
掌握angular2.0+springboot+mybatis技术栈，nginx的基本代理使用，数据库mysql的使用，基本linux操作进行发布部署。

## 2. 题目
使用上述技术栈完成用户注册、登录、修改密码的系统开发，linux环境发布部署。

## 3. 要求
1. 申请github账号，并创建代码仓库，把代码上传，开发过程中使用git来管理代码。
2. 前端页面开发请使用Visual Studio Code作为开发工具，后端java开发请使用IntelliJ IDEA作为开发工具。
3. 开发过程中，应用运行在本地，使用公共提供的mysql数据库。待进入职场条件具备后，部署在公共应用服务器中。
4. 用户信息存储的时候至少分为两张表，一张表存储用户名密码等，另一张表存储更多详细信息，如住址，邮箱地址等。在注册的时候使用数据库事务完成插入，保证两张表数据一致。
5. 各自建立自己使用的表，表名统一加前辍，姓名的首字母缩写(如遇到重复后建者加序号，如张三为zs1)，使用小写字母，并采用下划线分割。如张三的用户信息表zs_user_base，张三的用户详细信息表zs_user_detail

## 4. 学习资料
- [angular2入门教程] https://www.w3cschool.cn/angular2/
- [springboot入门教程] http://c.biancheng.net/spring_boot/
- [springboot整合mybatis] https://www.jianshu.com/p/541874714907
- [nginx入门教程] https://www.w3cschool.cn/nginx/

## 5. 开发服务器信息

1. 数据库 已通过如下建库语句创建好了库
``` sql
CREATE DATABASE IF NOT EXISTS c1test01 DEFAULT CHARSET utf8 COLLATE utf8_general_ci; 
```

| 项目        | 内容   |
| --------   | --------  | 
| 数据库地址      | 101.52.252.44   |
| 数据库端口      |   80   |
| 数据库用户        |   test01    |
| 数据库密码        |   test01#@abc    |
 

## 6. 过程指引

#### 6.1. 网页端开发提示

1. nodejs
    安装包：https://nodejs.org/download/release/v10.17.0/node-v10.17.0-win-x86.zip
    版本：v10.17.0 附带npm版本：6.11.3
2. Visual Studio Code
    安装包: https://code.visualstudio.com//
3. Angular-cli
    版本：1.7.2
    对应Angular版本：5.2.0
    npm全局安装Angular-cli命令：npm install -g Angular-cli@1.7.2
    npm命令大全：https://blog.51cto.com/u_12173069/2088821
    官网：https://angular.cn/cli
    介绍：Angular-cli不仅仅能够创建一个Angular项目，还提供了快捷命令生成组件、模块、路由、服务等等
4. Angular
    官网：https://angular.cn/docs
    快速体验：StackBlitz 在线开发环境
    官方demo：https://angular.cn/generated/live-examples/toh-pt6/stackblitz.html
    官方demo源码下载：https://angular.cn/generated/zips/toh-pt6/toh-pt6.zip
    如何学习Angular：https://www.zhihu.com/question/34083190
5. TypeScript
    学习：https://segmentfault.com/a/1190000014121295?utm_source=sf-similar-article
6. 前端代码规范：https://guide.aotu.io/index.html
7. JavaScript 资源大全中文版：https://github.com/jobbole/awesome-javascript-cn

#### 6.2. JAVA端开发提示

1. 使用msyql客户端软件如navicat连接数据库，并创建表
2. 写springboot helloworld服务，尝试使用如postman的工具发起post请求
3. 写springboot对数据库一张表的增删改查的服务，并使用postman进行测试
4. 按业务场景完成后台服务的编写，并使用postman工具进行测试
5. 尝试与前端angular集成

## 7. 答疑联系
QQ群：871557745 （入群申请备注姓名）
