## 流程控制
  1. 条件语句
  2. 复合语句
  3. while loop
  4. for loop
  5. 操作符
  6. 生成式
  7. 异常
  8. 文件处理
  
### 条件语句
  1. if True:语句
  2. if else
  3. if elif elif  else
  
### 复合语句
  1. if conditon1 and contion2:
  2. if condition1 or condition2:
 
### while loop
  1. while True:pass
  2. while n<10:pass
  
### for loop
  1. for i in range(10):print(i)
  2. for i in [2,3,6]:pass
  3. 可迭代的循环
  
### 操作符
  1. lambda Lambda expression
  2. if, elif, else Conditional expression
  3. and Boolean AND
  4. or Boolean OR
  5. not x Boolean NOT
  6. in, not in, is, is
  7. not,
  8. <, <=, >, >=, !=, ==
  9. Comparisons, including membership tests and identity tests
  10. | Bitwise OR
  11. ^ Bitwise XOR
  12. & Bitwise AND
  13. <<, >> Shifts
  
  
### 生成式
  1. 列表生成式    [i*2 for i in range(5)]
  2. 多个循环     [x+y for x in range(1,5) for y in range(2,4)]
  3. 条件判断筛选 [x for x in range(20) if x%2==0]
  4. 字典生成式  {x: x+10 for x in range(0, 5)}
  5. 集合生成式  {x+10 for x in range(0, 5)}  
  ...

### 异常
  1. try:  except
  2. try except else
  3. try except else finally
  ##### else 接在except后面，如果一个我们设置的异常都没有，那么执行else语句
  #####  finally 不管是否有异常捕获，都会执行
