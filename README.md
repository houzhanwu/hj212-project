# 基于HJ212协议的污染源在线监测平台

####  **介绍** 
基于HJ212协议的污染源在线监测平台,包含水、气、声，污染数据接入，接入设备需符合HJ212-2005/2017协议，会尽快完善，欢迎广大爱好者共同完善！

####  **软件架构** 
1.  数据库：简单版：Mysql、redis、复杂版本：hbase、es
2.  中间件：Kafka
3.  第三方协议：HJ212-2005、HJ212-2017
4.  网络协议：Tcp、Http
5.  框架：
        简单版： springboot、springmvc、mybatis、mybatis plus、shiro
                核心框架：Spring Boot
                安全框架：Apache Shiro
                视图框架：Spring MVC
                服务端验证：Hibernate Validator
                任务调度：Quartz
                持久层框架：Mybatis、Mybatis plus
                数据库连接池：Alibaba Druid
                缓存框架：Ehcache
                日志管理：SLF4J、Log4j
                工具类：Apache Commons、Jackson、Xstream、
                后端渲染模板引擎: Thymeleaf
        复杂版本：springcloud版本

####  **包含功能** 

1.  污染数据查询
2.  站点地图（污染排口管理）
3.  数据审核、修约
4.  远程采集、补录数据
5.  设备反控、指令下发
6.  数据报警
7.  数据报表
8.  数据剔除
9.  传输有效率计算、总量计算
10. 一企一档
11. 视频监控、DVR管理、录像管理
####  **部分功能截图** 
![image text](https://gitee.com/houzhanwu/hj212-project/raw/master/screenshot/data.png)
![image text](https://gitee.com/houzhanwu/hj212-project/raw/master/screenshot/data_analysis.png)
![image text](https://gitee.com/houzhanwu/hj212-project/raw/master/screenshot/data_msg.png)
![image text](https://gitee.com/houzhanwu/hj212-project/raw/master/screenshot/device.png)
![image text](https://gitee.com/houzhanwu/hj212-project/raw/master/screenshot/map.png)


####  **通用功能** 
    系统权限
       基于shiro实现的rbac的权限管理，能够基于不同的角色控制到按钮权限级别
    数据字典
        对系统使用的枚举类进行预览、管理。
    核心工具
        系统对常用的工具类进行了封装，使用更加方便。
    代码生成
        基于volecity模板，可根据db生成单表的增删改查代码，包括菜单sql、dao、service、cotroller、js、html。
    在线用户
        查看在线的用户，支持强T退出。
    七牛对象存储
        支持第三方对象存储七牛云oss，需申请相应的账户信息。
    定时任务
        基于quartz实现的动态定时任务。
    Swagger 文档
        api开发方便在线调试，简化了与前端的对接。
    基于 JWT 实现的 API 模块
        简化了app的api开发基础工作。

####  **沟通交流** 

1.  技术QQ: 1358850447(添加注明来意)
2.  QQ交流群：
3.  微信交流群：
