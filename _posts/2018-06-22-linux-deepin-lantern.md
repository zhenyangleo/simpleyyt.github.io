---
layout: post
title: linux(deepin)下安装lantern问题解决
---

在linux deepin中直接安装从github下载的lantern的deb文件后，点击应用按钮是不能打开lantern的。

这是由于缺少一个lib库,运行 

`sudo apt-get install libappindicator3-1` 

安装即可解决。

