# git checkout study
selfteaching

record of studing python

3.19
备注
另外，以下几个链接先放在这里，未来你会返回来参考它们，还是不断地参考它们：

关于表达式：https://docs.python.org/3/reference/expressions.html
关于所有操作的优先级：https://docs.python.org/3/reference/expressions.html#operator-precedence
上一条链接不懂 BNF 的话根本读不懂：https://en.wikipedia.org/wiki/Backus-Naur_form
Python 的内建函数：https://docs.python.org/3/library/functions.html
Python 的标准数据类型：https://docs.python.org/3/library/stdtypes.html
另外，其实所有的操作符，在 Python 内部也是调用函数完成的……

https://docs.python.org/3.7/library/operator.html

Good example of continue & break:

for n in range(2, 100):
    
    if n == 2:
        print(n)
        continue        # 忽略其后的语句开始下次循环 for n in range(2, 100):
    
    for i in range(2, n):
        if (n % i) == 0:
            break       # 从此结束当前循环 for i in range(2, n): ，开始执行循环 for i in range(2, n):之后的语句，即开始下次循环 for n in range(2, 100):
    
    else:               # 下一行的 print(n) 事实上属于语句块 for i in range(2, n):
        print(n)        # 整个循环结束，都没有发生 break 的情况下，才执行一次 print(n)
        
        
        awesome github!
        
        
Well

3.20

函数：

（1）关键字参数:sorted()
（2）位置参数：dimod()
（3）可选位置参数:pow()

ord() & chr()

input() 这个内建函数的功能是接收用户的键盘输入，而后将其作为 字符串 返回。

in:
    print('\'')
out:
    '

\t = tab ; \n = enter

与大量 “前置引用” 相伴随的是知识点的重复出现。

3.21

<img width="809" alt="2a62035bf8f8acd2924fbf70522d2b2" src="https://user-images.githubusercontent.com/97277390/159297335-804e50f1-ca50-42cc-8218-c7d807894a13.png">

<img width="256" alt="a7d69fb26a00838e3eb3014d787b9e8" src="https://user-images.githubusercontent.com/97277390/159297397-f6a33c56-7c25-4721-ac17-50e40fa44c79.png">!

[Uploading e1cd541b200198d13f8e4d37f70f580.png…]()
