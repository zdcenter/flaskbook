---
description: flask 学前预热
---

# 第一章：Url 组成部分详解

URL ：是 Uniform Resource Locator 的简写

URL地址的构成：[s](http://www.xxx.com/page/s)cheme://host:port/path/?query-string=xxx\#anchor

。scheme：代表的是访问协议，一般为http或https ，ftp 等

。host：主机名，域名，ip；

。port：端口号。默认80，在浏览器中可以省略

。path：查找路径

。query-string：查找字符串；

。anchor：锚点，后台一般不要管，前端用来做页面定位

注意：URL 中的所有字符都是ASCII 字符集，如果在浏览器中出现其他字符集如中文，浏览器会进行编码在传输



