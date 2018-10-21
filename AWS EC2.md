# 1.在阿里云注册域名，开启解析，添加A记录

# 2.关于Amazon云服务
## 1. [注册AWS账号](https://aws.amazon.com/cn/)
有一个可以用学生优惠注册的，但是登陆的之后的账号权限被限制了还没有解决，所以推荐自己直接注册但是需要信用卡

## 2. [创建AWS EC2服务器](https://docs.aws.amazon.com/zh_cn/AmazonRDS/latest/UserGuide/CHAP_Tutorials.WebServerDB.CreateWebServer.html)
我使用的是ubuntu18的系统

## 3. [登陆到服务器](https://docs.aws.amazon.com/zh_cn/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html)
之前应该可以用网页登陆，但是现在Chrom和Firefox都不能用JAVA插件,所以用PuTTY

## 4. [在服务器上配置apache服务](https://www.howtoing.com/how-to-install-linux-apache-mysql-php-lamp-stack-ubuntu-18-04)
一开始使用tomcat但是服务一直打不开

## 5. 此时在自己电脑ping 服务器公网IP如果ping 不同,在EC2安全组中将入站的设置为全部流量

## 6. [设置apache配置指定为自己的域名](https://blog.csdn.net/aa3115386/article/details/50782725)

## 7.正在配置Wordpress博客，了解一下简单的html
