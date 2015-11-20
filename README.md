项目介绍
========
### 什么是接口文档管理工具?
一个用PHP编写的在线API文档管理系统；其致力于快速解决团队内部接口文档的编写、维护、存档，以及减少团队协作开发的沟通成本。
### 特点
* 轻量级
* 架构简单轻巧利于二次开发
* 部署维护方便

项目部署
========
1. 在MySQL中新建api数据库，并执行 db.sql文件
2. 在./MinPHP/core/config.php配置文件中修改数据库连接信息
3. 把项目部署到Apache或Nginx中即可

使用说明
========
1. 当前版本(v1.1)版本只做了简单权限控制，一是有权限；二是无权限。
2. **游客** 只能查看接口分类和接口信息 __无增删改查权限__
3. 默认的管理员有两个分别为admin(密码:654321)与root(密码:123456)。
4. 密码已经采用MD5加密存储，如果想要修改密码可先登录进去再通过页面修改。当然也可以直接修改数据库。

原作者信息
==========
* :email:	gongcoder@gmail.com
* qq:	309581329

最后
====
非常欢迎大家贡献代码，让这个项目成长的更好。
