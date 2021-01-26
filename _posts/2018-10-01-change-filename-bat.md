---
layout: post
title: 如何批量指定修改文件名【学生学号转姓名（身份证号）】
---

终于不用让学生自己修改了！终于不会出错了！不容易！

<!--more-->

首先要利用excel表格生成命令：

![excel生成命令截图](https://zhenyangleo.github.io/post-image/20181001-%E4%BB%A3%E7%A0%81%E7%94%9F%E6%88%90%E5%85%AC%E5%BC%8Fexcel.png)    
其中：C2是修改前的文件名，B2是修改后的文件名。后缀可以根据自己的需要去修改，如果是批量命名其他文件格式的文件名的话可以用到。    
ren命令指的是rename。    

[文件批量修改指定文件名命令生成excel下载](https://share.weiyun.com/5NZYvdN)

分别将修改前和修改后的名称一一对应复制到excel表格中，生成公式，把公式复制到新建的文本文件中，然后修改后缀为bat文件。    

将bat文件放入要批量命名的文件同一个文件夹下双击运行即可！（如果要bat文件运行后不自动退出，命令最后一行加入“pause”。）

如想要修改文件名为，比如此例中修改为“学号-姓名”的格式，只需要适当修改下代码即可：    
如图：    
![生成学号-姓名格式文件](https://zhenyangleo.github.io/post-image/20181001-%E4%BB%A3%E7%A0%81%E7%94%9F%E6%88%90%E5%85%AC%E5%BC%8Fexcel-%E5%AD%A6%E5%8F%B7%2B%E5%A7%93%E5%90%8D.png)
