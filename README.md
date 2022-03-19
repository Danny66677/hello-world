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
        
        




