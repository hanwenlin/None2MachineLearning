### 整数
    1. 赋值 a = 10 b = -2
    2. 强制转换  int(0.5)  int(4.3) int(-2.6) int('10')  但是int('10.5')错误
    3. 运算  + - * / // ** %   注：5/2 = 2.5 5//2 = 2 **乘方  x += y =>> x = x+y (+=,-=,/=,*=)
    
### 浮点数
    1. 赋值 a = 12.3 b = .44  c = 3e6  前面的是系数，后面的是指数  4E2 = 4*10^2 = 400.0
    2. 强制转换 float('2.5') float(3)
    3. 运算
        1. round()   返回四舍五入的值，round(3.1416,3) = 3.142
        2. abs()    绝对值
        3. pow(x,y)   x的y次方  pow(5,2) = 25

### bool值
    1. 定义 my_var = True
    2. 转换 bool(1)
    3. 0，空，None  为False，其它均是True
    4. and or not       and有一个错误就返回，or有一个正确就返回
    5. 逻辑运算符  < <=  > >= == != is (is not)
    6. None 特殊字符，不是False，逻辑运算时可以是False的


### 字符串
    1. '' or ""  name ='hanwenlin'  单引号，双引号一样的
    2. ''' '''  or """ """ 多行字符串
    3. 字符串里面有',则使用""；有",则使用''
    4. str(10)   '10'
    5. 转义字符\    \\  \'  \"  \a  \b  \f  \n  \r  \t  \uxxxx  \Uxxxxxx  \v \ooo \xhh...
    6. name = u'hanwenlin'  或者 name = b'hanwenlin'
    7. path = r'C:\User\Admin'   当使用文件夹等，必须使用raw string 即r''
    8. 字符串方法
        1. str.replace('old','new')
        2. str1 + str2
        3. str.title()  每个单词大写开头
        4. str.lower()    str.upper()   大小写
        5. str.strip()  str.lstrip()  str.rstrip()    str.strip('12') 去掉首尾的1和2 默认去掉开始和末尾的空格，换行符
        6. str.startswith(str2)   str.endswith()           字符串是否以str2字符串开头
        7. str.split()                  text.split('.',2)  text=text = '10.13.37.1'
        8. ' '.join(text)    text为列表，元祖等
        9. str.isspace()            是否是空字符串 \t ' ' \n都返回True
        10. str.isalpha()  .isalnum()  .isdigit()  .islower()    .isupper()   .istitle()   .isspace()   
        11. bin()  hex()    range()   type()    len()   format()  
        
 ### 列表
    1. 定义 my_list = []  my_list = list()
    2. 一个元素，多个元素，嵌套列表 [[1,2],[4,5,7]]
    3. list.extend()  .append   .pop    .push
    4. list.remove(4)   删除4   list.insert(4,'one')  第五个位置插入'one'
    5. list.index(5)  5在列表中的位置
    6. len(list)   min()   max（） list.count()  list.reverse()反向
    7. list.sort()      sorted(list)  sort()原列表发生了改变，返回None  sorted()原列表不变，返回为排序后的结果
    8. ==  ！=  in   not in
    9. 切片
        1. list[3]
        2. list[1:4]
        3. list[:]
        4. list[::-1]    反向
        5. list[1:5:2]      #相隔两个取
        
        
        
### 集合   
    1. 定义  my_set  = set()
    2. 一个元素     {1}   {1，}
    3. 多个元素，集合里面可以包含集合，列表等
    4. my_set.add()  my_set.remove() my_set.discard()  my_set.pop() my_set.clear() x in my_set
    5. my_set.update([4,5])     添加多个元素
    6. - 差集  |并集  &交集   ^ 和&相反    set1 -set2
    7. len(my_set)
    8. 集合切片
    9. list,tuple转成集合，就是去重了，顺序也变了，集合无序不重复的
    
    
### 元祖
    1. 和list基本一样，只是不可变
    2. 定义  my_tuple = ()  my_tuple = tuple()
    3. my_tuple = 1,  my_tuple = (1,)
    
### 字典
    1. my_dict = {}  my_dict = dict()
    2. 赋值，键值对 key：value
    3. my_dict[key1]  = value1
    4. my_dict.get(key)  my_dict[key]不存在会报错
    5. my_dict.keys()  my_dict.values()   my_dict.values()
    6. len(my_dict)
    7. key in my_dict
      
    
