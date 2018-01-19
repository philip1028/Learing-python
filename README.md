# Learing-python
self record to learn python in 2017

    * 数据类型 & 变量

    数据类型有4种：
    字符串 - 表示一串字符，需要用''或""引起来  (eg. "hello world")
    整数  (eg. 111)
    浮点数 - 就是有小数点  (eg.3.99， 3.0)
    bool（布尔） - 这个比较特殊，是用来表示逻辑“是”“非”的一种类型，它只有两个值，True和False。（注意这里没有引号，有了引号就变成字符串了）

#  python 3.64版本
控制流语句:
   
   if name == 'Alice':             # if 的条件求值必须是 True or False。if条件为真，则执行子句，否则结束。            
      print ('Hello, Alice.')
   elif age < 12:                  # 放在if后，不止一个if条件的时候，则用elif等同于if的作用。因为if只可以有一个，elif可以有多个。
      print ('You are not Alice, little kid.')
   else:                           # else跟在if后面，当if/elif条件为False,再执行else语句。else语句不包含条件。
      print ('Hello, you are neither Alice or a little kid.')
  
 # while循环语句：  while代码条件一直为Ture，则一直执行。
  while Ture:
      print('Please input your name.')
      name = input()
      if name != 'Joe':
         continue
      print('Hello, Joe. What is the passwords?')
      password == input()
      if password == 'cat':
         break
  print('Access granted.')
