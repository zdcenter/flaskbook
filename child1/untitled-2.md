---
description: 配置文件config.py 的详解
---

# 2.3 config 配置文件

可以把一些配置信息放入到config.py中， 比如开启debug模式，把数据库连接信息放入到里面

在主程序中通过2种方法调用：

1. app.config.from\_object\(config\)调用，这种需要在前面import config

2. app.config.from\_pyfile\('config.py'\)调用，这个是直接使用config.py文件config.py不一点要使用py文件也可以是txt文件



