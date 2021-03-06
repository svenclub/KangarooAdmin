
### KangarooAdmin 轻量级权限管理框架

### 项目说明
-------------
1. KangarooAdmin 是以SpringMVC+Shiro+Mybatis为核心开发的精简后台基础系统。
2. 包含用户管理,角色管理,部门管理,权限管理,菜单管理,日志管理等常用业务模块。
3. 使用AdminLTE作为前端UI框架。
4. 第三方Mybatis-plus作为ORM框架。
5. Encache权限缓存。
6. FreeMarker模板,页面拆分,封装公共部分。
7. Druid数据源,数据库监控。
8. 报表支持。

### 技术选型
-------------
AdminLTE、Spring MVC、Shiro、Mybatis、Mybatis-Plus、Mysql、Maven

### 快速开始
-------------
1. 创建数据库AdminLTE-admin,导入resource/sql/AdminLTE-admin.sql
2. cd ~/AdminLTE-admin
3. mvn clean package -Dmaven.test.skip=true
4. mvn jetty:run
5. http://localhost:8080/KangarooAdmin,账号/密码:admin/123456


### 实例截图
-------------
![](https://git.oschina.net/uploads/images/2017/0914/161552_cb781545_89451.png "1.png")
![](https://git.oschina.net/uploads/images/2017/0914/161612_2616eeed_89451.png "2.png")
![](https://git.oschina.net/uploads/images/2017/0914/161619_db1dd09f_89451.png "3.png")
![](https://git.oschina.net/uploads/images/2017/0914/161627_7e08a1ea_89451.png "4.png")

说明:手动修改admin的密码可使用src/test/java下的TestAdmin生成admin的密码。
