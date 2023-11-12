## Python-Course

Python课程学习笔记

### 1 Python简介

Python由荷兰国家数学与计算机科学研究中心的Guido van Rossum于1990年代初设计的计算机编程语言。Python提供了高效的高级数据结构，既支持面向过程的编程也支持面向对象的编程。Python语法和动态类型，以及解释型语言的本质，使它成为多数平台上写脚本和快速开发应用的编程语言，随着版本的不断更新和语言新功能的添加，逐渐被用于独立的、大型项目的开发。

Python 3.0 于 2008 年 12 月 3 日发布常被称为 Python 3000，或简称 Py3k。相对于 Python 的早期版本，这是一个较大的升级。

### 2 Python语言基础

#### 2.1 缩进

python使用缩进来表示代码块，不需要使用大括号 {}

缩进的空格数是可变的，但是同一个代码块的语句必须包含相同的缩进空格数。

```
if True:
  print("True")
else :
  print("False")
```

#### 2.2 注释

单行注释使用 # ，多行注释使用多个 # 或 ''' """

```
# 第一行注释
# 第二行注释

'''
第三行注释
第四行注释
'''

"""
第五行注释
第六行注释
"""
```

#### 2.3 import

python中使用import导入模块，使用 from import 导入函数

```
导入模块 import somemodule
导入模块某个函数 from somemodule import function
导入模块多个函数 from somemodule import func1, func2
导入模块全部函数 from somemudle import *
```

### 3 数据类型

python3中数据类型有 Number、String、bool、List、Tuple、Set、Dictionary

变量命名遵循以下规则：















