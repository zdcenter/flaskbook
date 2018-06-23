---
description: debug 6种开启模式
---

# 2.2 Debug模式详解

**debug开启的好处**

1. 程序出现问题的时候，会有提示错误的信息，方便查找；
2. 在修改python的代码后，都不需要重新点运行，直接在浏览器上就能开到修改后的结果

**debug 开启方式：**

1. 在app.run\(\)里面设置一个参数：debug=True ；
2. 在app.run\(\)前面加入 debug = True；
3.  app.debug = True;
4. 通过配置参数的形式：app.config.update\(DEBUG=True\)
5. 通过配置文件app.config.from\_object\(config\)，其中配置文件信息：DEBUG = True
6. app.config.from\_pyfile\('config.py'\); 其中config.py 可以是其他类型的文本文件

