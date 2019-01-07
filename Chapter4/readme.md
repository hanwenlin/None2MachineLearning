**函数是什么?**   
函数一词来源于数学，但编程中的「函数」概念，与数学中的函数是有很大不同的，具体区别，我们后面会讲，编程中的函数在英文中也有很多不同的叫法。在BASIC中叫做subroutine(子过程或子程序)，在Pascal中叫做procedure(过程)和function，在C中只有function，在Java里面叫做method。

**定义: 函数是指将一组语句的集合通过一个名字(函数名)封装起来，要想执行这个函数，只需调用其函数名**  
**特性**  
1. 代码复用，减少重复代码
2. 代码变得更加容易维护
3. 程序变得更加扩展

###  函数（无参数）
    1. 没有任何操作，占位的
    def fun():
      pass
    2. 返回值  
     def fun():
      return 'hello'
    3. 返回None,打印 
    def fun():
      print('hello,world')
      
      
### 函数（有参数）
    形参：形参变量只有在被调用时才分配内存单元，在调用结束时，即刻释放所分配的内存单元。因此，形参只在函数内部有效。函数调用结束返回主调用函数后则不能再使用该形参变量  
    实参：实参可以是常量、变量、表达式、函数等，无论实参是何种类型的量，在进行函数调用时，它们都必须有确定的值，以便把这些值传送给形参。因此应预先用赋值，输入等办法使参数获得确定值  
    1. 位置参数
    def fun(name,age):
        print(name)
    fun('zhangsan',23)
    
    2. 默认参数
     def fun(name,age，country='CN'):
        print(name)
     fun('zhangsan',23)         默认参数也可以在调用时修改fun('li4',35,'USA')
     
     3. 关键参数
        正常情况下，给函数传参数要按顺序，不想按顺序就可以用关键参数，只需指定参数名即可，但记住一个要求就是，关键参数必须放在位置参数之后。  
        stu_register(age=22,name='alex',course="python",)
        
     4. 非固定参数 *args, **kwargs
     def fun(a,b=4,*args,**kwargs):
        pass
     *args参数是剩余的所有参数，**kwargs是字典参数  
     fun('han',5,7,8,one=1,two=2)  
     {'a': 'han', 'b': 5, 'args': (7, 8), 'kwargs': {'one': 1, 'two': 2}}
     
        
        
        
    
