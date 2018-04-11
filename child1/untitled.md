# 2.1 默认创建的第一个程序

```text
#从flask包中导入Flask这个类
#Flask这个类是程序的核心，以后很多操作都是基于这个类的
#如注册Url，注册蓝图等都是基于这个类的
from flask import Flask

#实例化Flask类，对象为app，传递__name__做为参数
#传递__name__的作用有2个：
#1.可以规定模板和静态文件的查找路径；
#2.以后一些插件如：flask-migrate，flask-SQLAlchemy如果报错了，可以通过这个参数找到具体的位置
app = Flask(__name__)

#注册一个装饰器
#就是将URL 首页地址映射到hello_world这个视图函数去
@app.route('/')
def hello_world():
    return 'hello world'

#如果作为主文件运行，就执行app.run()这个方法；
if __name__ == '__main__':
    app.run()    #flask中的一个测试服务器
```





