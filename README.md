  
grunt搭建的前端开发环境
===================================
本环境实现css、js的修改监听，
实现一个命令自动编译css、js。

###命令介绍

grunt         该命令将合并制定的js并压缩，编译sass文件成css并压缩
grunt watch   该命令用来监听指定的文件的变动，这里监听了js和scss的变动
grunt watch:script 监听JS文件
grunt watch:css   监听scss文件
grunt uglify  合并&压缩JS
grunt compass 编译SCSS文件，生成压缩后的CSS
  
grunt搭建的前端开发环境
===================================
本环境实现css、js的修改监听，
实现一个命令自动编译css、js。


###命令介绍

grunt   该命令将合并制定的js并压缩，编译sass文件成css并压缩
grunt watch 该命令用来监听指定的文件的变动，这里监听了js和scss的变动
css 使用sass语法编写，运行命令
实现css、js修改监听

  
中标题
-----------------------------------
  中标题一般显示重点项,类似html的\<h2\><br />
  你只要在标题下面输入------即可
  
### 小标题
  小标题类似html的\<h3\><br />
  小标题的格式如下 ### 小标题<br />
  注意#和标题字符中间要有空格

### 注意!!!下面所有语法的提示我都先用小标题提醒了!!! 

### 单行文本框
    这是一个单行的文本框,只要两个Tab再输入文字即可
        
### 多行文本框  
    这是一个有多行的文本框
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可
    这里你可以输入一段代码

### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧
    public class HelloWorld {

      /**
      * @param args
        */
        public static void main(String[] args) {
            System.out.println("HelloWorld!");

        }

    }
### 链接
1.[点击这里你可以链接到www.google.com](http://www.google.com)<br />
2.[点击这里我你可以链接到我的博客](http://guoyunsky.iteye.com)<br />

###只是显示图片
![github](http://github.com/unicorn.png "github")

###想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com
[![image]](http://www.github.com/)
[image]: http://github.com/github.png "github"

### 文字被些字符包围
> 文字被些字符包围
>
> 只要再文字前面加上>空格即可
>
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
> 但> 只能放在行首才有效

### 文字被些字符包围,多重包围
> 文字被些字符包围开始
>
> > 只要再文字前面加上>空格即可
>
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
>
> > > > 但> 只能放在行首才有效

### 特殊字符处理
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>



* 在行首加点
行首输入*，空格后输入内容即可
    