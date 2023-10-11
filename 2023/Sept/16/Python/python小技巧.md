# pYTHON 

### ① Lambda表达式

> lambda 表达式 会返回一个函数对象
> 
> lambda x : x**2

```python
<function <lambda> at 0x000001A67FBD8040>  # 16位的16进制地址
```

***

### ② Slicing 切片

```python
s = "apple"

s[0::-1]  # 'a'

s[0::1]  # 'apple'

s[::-1]  # 'elppa'

'''
如果[::-1]代表从end，每次走一步，到start；
那么[0::-1]为什么还是从start开始？
'''

```

***

### ③ DateTime 时间库

```python
import datetime as d

time = d.datetime

print(time.now())  # 当前时间： 2023-09-16 11:50:56.227045
```

***

### ④ Palindrome回文数

>  "aba" 就是回文数
> 
>  "LjL" 也是回文数

***

### ⑤ 阶乘

```python
import math
factorial = math.factorial(5)  # 120
factorial = math.factorial(10)  # 362880
```

***

### ⑥ 最大公约数 

```python
gcd = lambda a,b:a if b==0 else gcd(b,a%b)
```