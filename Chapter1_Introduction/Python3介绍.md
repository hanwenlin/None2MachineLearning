### 一、Python2与Python3的区别
    1. python2在python2.7,以后不再更新，2020那年不再有服务支持
    2. python3中print()是一个函数，而不是一个语句
    3. python3中的str都是unicode类型，只有input,没有raw_input
    4. 很多模块的名字发生了改变
    5. 在python3里，reduce()函数已经从全局名字空间移除，现在被放置在fucntools模块
    6. 在python3里，apply()函数不再存在；必须使用星号标记
    7. ...

### 二、Python安装以及编辑器
    1. [python 官方网站](https://www.python.org/)
    2. 选择[pycharm编辑器](http://www.jetbrains.com/pycharm/)  可以在网上找到破解码
    3. 配置环境变量
    4. IDE 集成开发环境
    5. Jupyter

### 三、基本知识点
    1. 查看版本号
  ```
  import sys
  print(sys.version)
  ```
  
### 四、语法
    1. 缩进代替括号
    2. 缩进不是tab键，而是是个空格
    3. 空行 \r,\r\n,\n  
    4. 注释
        1. Hash (#), space and then comment  # José Jiménez says hello
        2. Source code, two spaces, hash (#), space and then comment:   print('My name... José Jiménez') # José Jiménez says hello
        3. 多行注释 '''comments'''  or """comments"""  可以换行，一般都是换行的
    5. 文档字符串
        在模块，函数，类的第一个多行注释就是文档字符串
    
### 五、变量  
    1. 变量规则
        1. 变量名是数字，字母，下划线(_)组成，不能是数字开头的
        2. 区分大小写，长度不受限制
        3. 不能用python关键字作为变量名
    2. 变量名使用规范
        1. 普通变量：用小写字母，用_分割，比如this_is_primer
        2. 全局变量名： 大写字母，用 _ 分割，PI = 3.1415926
        3. 模块名，包名：普通变量名差不多，小写字母，下划线 ad_stats.py
        4. 类名： 单词首字母大写   AdStats
        5. 实例变量：以_开头，其他和普通变量一样，_price
        6. 私有实例变量（外部访问会报错）： 以__开头（2个下划线），其他和普通变量一样 __private_var
        7. 专有变量： __开头，__结尾，一般为python的自有变量，不要以这种方式命名  __doc__
        8. 普通函数： 和普通变量类似 get_name() ,私有函数，两个__开头
        9. 文件名： 小写字母，和普通变量名一样
        9. 
