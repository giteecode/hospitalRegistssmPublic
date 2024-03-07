## 基于Java+ssm的医院挂号系统(源代码+数据库+11000字论文+开题)633

## 一、系统介绍
本系统分为管理员、医生、用户三种角色

### 1、用户：
- 注册、登录、医生预约、评价、收藏、健康资讯、客服咨询、充值、预约挂号管理、我的病历管理、个人收藏管理、个人中心、密码修改
### 2、医生：
- 注册、登录、个人坐诊管理、预约挂号管理(审核、添加病历)、用户病历管理、密码修改
### 3、管理员：
- 用户管理、科室管理、医生管理、医生坐诊管理、预约挂号管理、用户病历管理、健康资讯管理、轮播图管理、客服管理、新闻资讯管理

### 文档目录
![contents](./picture/picture1.png)
## 二、所用技术

后端技术栈：

- ssm
- spring
- springmvc
- MybatisPlus
- Mysql
- maven

前端技术栈：

- jsp
- element-ui

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上,Maven3.6, navicat, tomcat8

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、用户
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

### 2、医生：
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)

### 3、管理员：
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)

## 五、浏览地址

前台访问地址：http://localhost:8080/yyssmj/front/index.jsp
- 用户账号/密码：用户2/123456

后台访问地址：http://localhost:8080/yyssmj/jsp/login.jsp
- 医生账号/密码：医生2/123456
- 管理员账号/密码：admin/admin

## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件
2. 使用IDEA/Eclipse导入项目，若为maven项目请选择maven，等待依赖下载完成
3. 修改src/main/resources/config.properties里面的数据库配置
4. 配置tomcat将项目war包加到tomcat容器里面
5. 启动项目

