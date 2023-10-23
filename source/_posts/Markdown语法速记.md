---
title: Markdown语法速记
date: 2023-10-16 19:53:32
tags: Markdown
categories: 备忘和速记
---

## 一、标题

类 Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题）

类 Atx 形式是在行首插入1 到6 个 #，随#的数量增加，标题级数减少

## 二、字体

_倾斜_ *倾斜*  
__加粗__ **加粗**  
___加粗倾斜___ ***加粗倾斜***  
~~删除线~~  


## 三、分割线

****  
————————————  
-----  

## 四、引用

> 这是一段引用
>> 这是嵌套引用

## 五、表格

表头|表头|表头
---|:--:|---
1|2|3

表头|表头|表头
---|:---|---:
1  |2   |3

## 六、列表

- 无序列表：减号
  * 无序列表： 星号
    + 无序列表：加号
      1. 有序列表

## 七、代码

```C++
    // 代码段
    #include <isotream>
    using namespace std;
    int main()
    {
        cout << "hello world" << endl;
        return 0;
    }
```

## 八、段落和换行

段落：要创建段落，请使用空白行将一行或多行文本进行分隔。  
换行：在一行的末尾添加两个或多个空格，然后按回车键，即可创建一个换行

## 九、链接

### 超链接Markdown语法代码

1. [超链接显示名](超链接地址 "超链接title")，还有使用尖括号可以把URL或者email地址变成可点击的链接。  
2. [Chess](../images/testImage/chess.bmp)
3. [`Girl`](../images/testImage/Girl.bmp)
4. 百度：<https://www.baidu.com>

## 十、图片

![Chess](../images/Markdown语法速记/testImage/chess.bmp "Chess")
![Girl](../images/Markdown语法速记/testImage/Girl.bmp "Girl")
