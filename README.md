# test4Git

# ２.词法分析
一个 Python 程序是由一个解析器读取的。解析器的输入是一个由词法分析器生成的符号流。本章介绍了词法分析器如何将文件分解为符号。

Python 将程序文本以 Unicode 代码点的方式读入；源文件的编码格式由编码声明给出，其默认值为 UTF-8 ，详见[ PEP 3120 ](http://www.python.org/dev/peps/pep-3120)。源文件无法被解析时，会引发[ SyntaxError](https://docs.python.org/3/library/exceptions.html#SyntaxError) 异常。


