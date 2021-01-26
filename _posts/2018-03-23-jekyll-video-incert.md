---
layout: post
title: Jekyll中插入优酷视频的方法（2018年3月23日更新HTML5视频嵌入）
---

直接复制youku视频中的分享html代码在文章界面中粘贴即可！  

注意，按照jekyll的语法规则，可能要删除掉后边的`</embed>`最后这段代码

如下：

![优酷分享代码](https://zhenyangleo.github.io/post-image/20180224-%E5%88%86%E4%BA%AB%E4%BB%A3%E7%A0%81.png)  

<!--more-->

举个例子：

如果我想要把优酷中这个视频[Sully with Interstellar docking scene score](https://v.youku.com/v_show/id_XMzIwNDA4OTk5Mg==.html?spm=a2hzp.8253869.0.0)插入这篇文章中，那我需要在文章中插入以下代码：

`<embed src='http://player.youku.com/player.php/sid/XMzIwNDA4OTk5Mg==/v.swf' allowFullScreen='true' quality='high' width='480' height='400' align='middle' allowScriptAccess='always' type='application/x-shockwave-flash'>`

显示效果如下：    

*当然，请使用带有flashplayer播放器的浏览器播放，自测iPhone上的safari是无法播放的。*  

<embed src='http://player.youku.com/player.php/sid/XMzIwNDA4OTk5Mg==/v.swf' allowFullScreen='true' quality='high' width='480' height='400' align='middle' allowScriptAccess='always' type='application/x-shockwave-flash'>

**2018年3月23日更新**    
更新插入HTML5视频的方法，可以在iPhone上播放！    
代码如下    
`<iframe width="400" height="300" src="http://player.youku.com/embed/XMzIwNDA4OTk5Mg==" frameborder="0" allowfullscreen></iframe>`    
其中`embed/`后插入的是优酷视频ID，可以在优酷视频的播放页面中找到。    
效果如下：    
<iframe width="400" height="300" src="http://player.youku.com/embed/XMzIwNDA4OTk5Mg==" frameborder="0" allowfullscreen></iframe>


