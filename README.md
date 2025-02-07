# Python
## 知识点
### 命名规则
- 以字母下划线开头，后跟字母、下划线和数字；不准以数字开头
### 关键字（保留字）
- 是指在编程语言内部定义并保留使用的标识符，python3.x有35个保留字，分别为：
```python
#引入模块：
import keyword

k= keyword.kwlist
#查看保留字个数
print("python保留字个数:"+str(len(k))+"个")
#列出保留字
print(k)

# 打印出：
"""
python保留字个数: 35个

['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 
'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 
'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda',
 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 
'with', 'yield']
"""

```
### 源文件扩展名
- python一般常用扩展名(后缀名)为.py
### 程序设计IPO模式
- I:Input输入，程序的输入
- P:Process处理，程序的主要逻辑
- O:Option输出，程序的主要输出
### 字符串比较规则
- 从第一个字符串开始，位置一一对应比较编码的大小，从字符串左边开始，依次比较每个字符，直接出现差异、或者其中一个串结束为止
### 注释
- #后面的为注释内容
```python
# 普通注释
print("hellow world") # 人生的第一个代码

"""
这是一个多行注释,
这种文档字符串不仅提高了代码的可读性，还便于其他开发人员理解你的代码。
"""
def python_one(text):
    """
    返回传入的文本。

    :param text: 需要返回的文本。
    :return: 传入的文本。
    """
    return text

```
### 数据类型
#### 浮点数
- 浮点数是带有小数的数字，它在Python中使用IEEE 754标准进行存储，存在范围限制（通常在-10^308到10^308之间），如果计算结果超出这个范围，会产生溢出错误。
### 字典
- "键"可以是整数或字符串，也可以是函数、元组、类等不可变类型
### python
#### 语言特点
- 开源免费、优秀的扩展性和跨平台、是脚本语言、采用解释方式执行
#### 描述
- python属于脚本语言，脚本语言采用解释方式执行。解释是将源代码逐条转换成目标代码同时逐行运行目标代码的过程。
#### 循环
- break 意为结束循环，continue是结束这个循环进入下一个循环
### python中特殊含义的符号
- 算术运算符

    +：加法运算符，用于将两个对象相加。

    -：减法运算符，用于从一个数中减去另一个数或得到一个数的负数。

    *：乘法运算符，用于将两个数相乘或返回一个重复若干次的字符串。

    /：除法运算符，用于将一个数除以另一个数。

    %：取模运算符，返回除法的余数。

    **：幂运算符，返回一个数的另一个数次幂。

    //：取整除运算符，返回商的整数部分。
- 比较运算符
    
    ==：等于运算符，用于比较两个对象是否相等。
    
    != 或 <>：不等于运算符，用于比较两个对象是否不相等。
    
    ">"：大于运算符，用于返回一个值是否大于另一个值。
    
    <：小于运算符，用于返回一个值是否小于另一个值。
    
    ">="：大于等于运算符，用于返回一个值是否大于或等于另一个值。
    
    <=：小于等于运算符，用于返回一个值是否小于或等于另一个值。

- 赋值运算符
    
    =：简单赋值运算符，用于将一个表达式的值赋给一个变量。
    
    +=：加法赋值运算符，等同于 c = c + a。
    
    -=：减法赋值运算符，等同于 c = c - a。
    
    ***=：乘法赋值运算符，等同于 c = c * a。
    
    /=：除法赋值运算符，等同于 c = c / a。
    
    %=：取模赋值运算符，等同于 c = c % a。
    
    ***=：幂赋值运算符，等同于 c = c ** a。
    
    //=：取整除赋值运算符，等同于 c = c // a。

- 逻辑运算符
    
    and：逻辑与运算符，如果两个操作数都为真，则返回真。
    
    or：逻辑或运算符，如果任一操作数为真，则返回真。
    
    not：逻辑非运算符，用于反转操作数的逻辑状态。

- 其他符号
    
    #：用于单行注释。
    
    """ 或 '''：用于多行注释。
    
    ()：用于函数调用、方法调用、类定义或元组。
    
    []：用于列表。
    
    {}：用于字典。
    
    @：用于装饰器。
    
    :：用于定义类或方法体。
    
    ->：用于函数定义后，添加元数据描述函数的返回类型。
    
    ">>>"：Python控制台命令输入提示符。
- 