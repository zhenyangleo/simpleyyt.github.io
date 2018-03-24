---
layout: post
title: 如何插入网易云音乐（HTML5播放器用iframe）
---

代码如下：    
`<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="330" height="86" src="//music.163.com/outchain/player?type=2&id=643466&auto=0&height=66"></iframe>`    

<!--more-->

注意每个值都需要加引号，如果不自动播放的话，一定要把后段代码中的`auto=1`修改为`auto=0`。    
曲目ID替换成想要播放的曲目的ID就可以了。**ID需要在官方生成的歌曲外链地址中提取，歌曲网址的中ID无效！**

效果如下：    
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="330" height="86" src="//music.163.com/outchain/player?type=2&id=643466&auto=0&height=66"></iframe>   
