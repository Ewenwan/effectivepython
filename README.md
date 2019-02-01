# Effective Python

[59个编写高质量Python代码的中文翻译版](https://guoruibiao.gitbooks.io/effective-python/content/)

[读书笔记博客](https://blog.csdn.net/if_it_is_deadline/article/details/80298777)

Hello! You've reached the official source code repository for _Effective Python_. To learn more about the book or contact the author, please [visit the official website](http://www.effectivepython.com).

[![Cover](./cover.jpg)](http://www.effectivepython.com)

In this repository you can browse all of the source code included in the book. Each item has its own file or directory containing the example code. Each file is annotated with which example snippet it came from within each chapter.

To run all the code for an item, just type `./item_01.py` into your shell and see what it prints out. Alternatively you can type `python3 item_01.py` or `python2.7 item_03_example_03.py` to run a specific version of Python.

To report a problem with the book or view known issues, please [visit the Errata page](./Errata.md).


# 序言
    自从 Scott Meyers 撰写 Effective C++ 以来，出现了很多以 Effective 开头的书籍。
    Effective 一词并不单单意味着 执行速度层面的高效率，同时还有 代码易读、易于测试
    易于维护、易于扩展、易于修改和易于多人协作等理念。
    
    目录:
      1.python风格(pythonic)
      2.函数 function  def 
      3.类与继承
      4.元类及属性，metaclass and dynamic attribute
      5.并发及并行，系统调用、子进程、C语言扩展
      6.内置模块
      7.协作开发
      8.部署，调试、优化、测试
## 1.python风格(pythonic)
    PEP 8 风格：
     使用space(空格)来表示缩进，不要使用tab(制表符)。
     类和函数中间空两行空行。
     类内方法函数之间空一行空行。
     函数、变量、属性应该用小写字母瓶邪，个单词之间以下划线相连。
     私有类实例属性以两个下划线开头；受保护的实例属性以单个下划线开头。
     常量全部用大写字母命名。
    
    pylint 是一款流行的python源码静态分析工具，可以检查代码是否符合PEP 8 风格
    
    
    
    
    
    
