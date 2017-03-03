#Welcome to use MarkDown

## 标题使用

    标题是每篇文章都需要也是最常用的格式, 在markdown中, 
    如果一段文字被定义为标题, 只需要在这段文字前加#即可

# 一级标题
## 二级标题
### 三级标题

## 列表

    在markdown下, 列表的显示只需要在文字前加上- 或 * 即可变成无序列表,  
    有序列表则直接在文字前加1. 2. 3. 符号要和文字之间加上一个字符的空格.

###无序列表

- 1
- 2
- 3
* 1
* 2
* 3

###有序列表

1. 1
2. 2
3. 3

##引用

>这是引用  
>>这也是引用

##图片与链接

    插入链接与插入图片的语法很像, 区别在一个!号
    图片为![]()
    链接为[]()
    
####插入链接
[百度](http://baidu.com)

####插入图片
![Mou icon](http://mouapp.com/Mou_128.png)  
<img src="E://img/the garden of words/1 (9).png">

##粗体与斜体

    Markdown的粗体和斜体也非常简单, 用两个*包含一段文本就是粗体的语法,  
        用一个*包含就是斜体的语法.

####粗体
**我是粗体.**  
*我是斜体*  
***我是粗体加斜体***  

##表格

    表格是我觉得markdown比较累人的地方.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

| username | sex    | age |
|----------|--------|-----|
| xiongzl  | male   | 25  |
| xiongq   | female | 23  |

##代码框
    如果你是一个程序员, 需要在文章里优雅的引用代码框, 在markdown下实现也非常简单,
    只需要两个`把中间的代码包裹起来就可以了.

`
public static void main(String args[]) {  
	System.out.printf("Hello World!");
}
`
<pre>
public static void main(String args[]) {  
	System.out.printf("Hello World!");
}
</pre>

##分割线

    分割线的语法只需要三个*号就可以了.  

***    
***











