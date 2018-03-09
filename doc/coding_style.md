Coding Style
===

编码风格
---
by: SoyaDokio  
ref: https://github.com/yanghuicpp/nginx-book/blob/master/source/appendix_a.rst

### 一、基本原则

1. 每行不能超过80列。

2. 不用TAB对齐，用空格。

3. 默认对齐单元是4个空格。

4. 用static和final修饰的变量，字母均为大写，单词间用下划线_间隔。

5. 使用/**/形式的注释，//形式仅用作翻译。

6. 中缀运算符的前后须空一格，如3 + 2以及a > 3。

7. 逗号、分号后须空一格，如foo(a, b, c)以及int i = 0; i < 2;

### 二、风格图示

![1](http://tengine.taobao.org/book/_images/code-style-2.JPG)

3. 类的注释的开始空一行。

4. 类的注释包括[暂时留空...]。

5. 若一行显示不下，首个折行空2个缩进单位/8个空格，之后折行的缩进保持与首个折行一致。

![](http://tengine.taobao.org/book/_images/code-style-3.JPG)

7. ~static结构体~的左花括号放在同一行上，且与关键字之间空一格空格。

9. 元素内容上下对齐。

![]()

8. 较大的结构体最开始空一行。

![](http://tengine.taobao.org/book/_images/code-style-1.JPG)

1. if/while/for/switch语句的左圆括号和关键字在同一行上，之间空一个空格。

1. if/while/for/switch语句的左花括号和关键字在同一行上，和圆括号之间空一个空格。

2. else关键字和两个花括号在同一行上，和左右花括号各空一格。

![]()

6. 结构体数组的花括号和内容之间空一个空格。

![](http://tengine.taobao.org/book/_images/code-style-4.JPG)

10. 注释上下对齐。

![](http://tengine.taobao.org/book/_images/code-style-8.JPG){:width="550px"}

16. 单行注释格式为/\* something \*/

![](http://tengine.taobao.org/book/_images/code-style-9.JPG){:width="550px"}

17. 多行注释的格式为：

```java
    /*
     * something
     */
```

![](http://tengine.taobao.org/book/_images/code-style-10.JPG){:width="550px"}

19. switch语句中，switch和case关键字上下对齐。


![](http://tengine.taobao.org/book/_images/code-style-11.JPG){:width="550px"}

20. 当条件表达式过长需要折行时，关系运算符须位于下一行的行首，并空2个缩进单位/8个空格，之后折行与上行对齐，同时右圆括号须位于单独的一行，并与上行对齐。

![](http://tengine.taobao.org/book/_images/code-style-12.JPG){:width="550px"}

21. else语句之前须空出一行。