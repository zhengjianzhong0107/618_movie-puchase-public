### 作者QQ：1556708905(支持修改、 部署调试、 支持代做毕设)

#### 支持代做任何毕设论、接网站建设、小程序、H5、APP、各种系统等

**毕业设计所有选题地址 [https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

**博客地址：[https://blog.csdn.net/2303_76227485/article/details/128707081](https://blog.csdn.net/2303_76227485/article/details/128707081)**

**视频演示：[https://www.bilibili.com/video/BV1cg4y1N7Az/](https://www.bilibili.com/video/BV1cg4y1N7Az/)**

## 基于ssm的电影购票系统(源代码+数据库)

## 一、系统介绍

本项目分为管理员与普通用户两种角色

- 前台
  - 普通用户注册、登录、注销
  - 用户信息修改：邮箱、密码、头像
  - 影片分类：按类型分类（国家、时间暂未实现）
  - 影片的信息浏览：影片的名称、导演、演员、简介及上映时间等
  - 影片排行推荐：可根据影片 票房 或 评分 进行推荐，推荐好评度高或售票量高电影
  - 观影的房间、座位的选择：用户选择观影的影院、房间、座位，用户不能选择已出售的座位
  - 用户的评价：用户登录后可对影片写一些评价
  - 订单信息查询：历史订单信息，包括金额、对应电影票、场次、座位等
- 后台
  - 对影片的信息进行管理：影片的名称、导演、演员、简介及上映时间等，对影片进行新增、删除、编辑等
  - 对影评信息进行管理：对评语进行修改、删除等。
  - 对所有电影院中影片价格进行修改
  - 对电影放映场次进行管理：增加，修改，下架场次
  - 对影院进行管理：增加修改影院
  - 对用户信息进行查询、修改等管理功能。
  - 对电影票订单信息进行查询和管理
  - 票房统计：票房数据可视化

## 二、所用技术

后端技术栈：

- ssm
- mybatis
- mysql

前端技术栈：

- Layui
- echarts

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7,Maven

源码+数据库脚本

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)

![contents](./picture/picture2.png)

![contents](./picture/picture3.png)

![contents](./picture/picture4.png)

![contents](./picture/picture5.png)

![contents](./picture/picture6.png)

![contents](./picture/picture7.png)

![contents](./picture/picture8.png)

![contents](./picture/picture9.png)

![contents](./picture/picture10.png)

![contents](./picture/picture11.png)

![contents](./picture/picture12.png)

![contents](./picture/picture13.png)

![contents](./picture/picture14.png)

![contents](./picture/picture15.png)

![contents](./picture/picture16.png)

![contents](./picture/picture17.png)

![contents](./picture/picture18.png)

![contents](./picture/picture19.png)

![contents](./picture/picture20.png)

## 五、浏览地址

前端访问地址：http://localhost:8989/

用户账号/密码：user/123456

管理员账号/密码：admin/123456  

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 使用IDEA/Eclipse/MyEclipse导入项目，请选择maven; 若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；
3. 修改mysql.properties 里面的数据库配置
4. 启动项目后端项目 
5. 访问  http://localhost:8989/

**注意事项：**

- tomcat 需要设置端口：8081 可在Api.js中修改相关配置
- 在tomcat配置文件添加 URIEncoding="utf-8" 以支持中文链接，否则演员图片和剧照无法正常显示

 
