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
