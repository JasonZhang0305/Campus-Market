# campus-market
## An used goods transaction platform based on Springboot

Main Tools: Eclipse + JDK8

Frameworks: Spring Boot

Database: Mysql5.7

Others：HTML, CSS, JS, Freemarker. 

Project Discription：This project is a c2c second-hand market trading platform. It is mainly aimed at college students to facilitate the exchange of second-hand goods between students. Users can register their own information on this website, post products, and can also contact sellers and buy products through this platform. This project not only implements user pages but also implements a backend management page. Administrators can operate the website through the backend management page. Additionally, I set a theme for the display page of the website based on my own university.

视频学习网址：https://www.bilibili.com/video/BV1Br4y117rm/?spm_id_from=333.337.search-card.all.click&vd_source=126a675e30d3918492f9fe1ca7b624d4
## 项目目录：  
 ![Project Directory](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/directory.png).  
  
## 项目导入
配置好所需要的开发环境，加载pom文件，修改配置文件，然后启动App.java即可。 

**要点！！**  
**1. 修改application-dev.properties文件**
填写你的数据库的账号和密码
spring.datasource.username=
spring.datasource.password=
修改上传和备份的路径      
![配置文件](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/properties.png). 
**2. 提前开启本机的数据库，启动程序后会自动连接Mysql**
**3. 在localhost的8081端口打开index页面，可以修改端口号**  
**4. 前端页面是freemarker文件，便于动态资源的传输**  

## 功能介绍 
### 客户端：
**1 用户注册登陆**
![登陆页面](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/login.png). 

**2 主页**
![主页](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/home.png)  

**3 左边展示台**
![左边展示台](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/left.png). 

**4 右边展示台**
![右边展示台](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/right.png). 

**5 页面底部**
![底部](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/bottom.png).  

**6 用户页面**
![用户页面](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/user.png). 

**7 用户求购页面**
![求购](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/want.png). 

**8 用户搜索框**
![搜索](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/search.png). 

**9 用户购买页面**
![购买](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/buy.png).  

**10 联系卖家**
![联系](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/connect.png).  

**11 卖出时状态**
![卖出](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/sell.png). 

**12 卖出后商品状态**
![卖出的商品](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/sellgood.png). 

### 后台管理系统：
**1管理系统**
![管理系统](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/administration.png). 

**2商品管理页面**
![商品管理](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/goods_admin.png).

**3学生管理页面**
![学生管理系统](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/stu_admin.png). 

**4后台推荐管理**
![推荐](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/recommend.png). 

**5推荐效果标签**
![推荐标记](https://github.com/JasonZhang0305/Githubimg/blob/main/imgc2c/rec_mark.png). 
