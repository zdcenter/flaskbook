---
description: flask 学前预热
---

# 第一章：认识web

## URL 组成部分详解

URL ：是 Uniform Resource Locator 的简写

URL地址的构成：[s](http://www.xxx.com/page/s)cheme://host:port/path/?query-string=xxx\#anchor

。**scheme**：代表的是访问协议，一般为http或https ，ftp 等

。**host**：主机名，域名，ip；

。**port**：端口号。默认80，在浏览器中可以省略

。**path**：查找路径

。**query-string**：查找字符串；

。**anchor**：锚点，后台一般不要管，前端用来做页面定位

**注意**：URL 中的所有字符都是ASCII 字符集，如果在浏览器中出现其他字符集如中文，浏览器会进行编码在传输

## web服务器和应用服务器+web应用框架

 **Web服务器**： 负责处理http请求，响应静态文件，常用的有Apache, Ngnix，IIS

**应用服务器：**负责处理逻辑的服务器。比如：php，python代码，是不能直接通过Ngnix来处理的，只能通过应用服务器来处理，常见的应用服务器有：uwsgi, tomcat 等。

**web应用框架**：一般使用某种语言，封装了常用的web功能的框架就是web框架。如 python中的**Flask，django**；php中的 **Laravel ，ThinkPhp**

