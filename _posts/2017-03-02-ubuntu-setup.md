---
layout: post
title: 自用ubuntu系统配置选项
---

**系统的配置**

* 终端更新系统

```
sudo apt-get update
sudo apt-get upgrade
```

<!--more-->

* 软件中心更新相关内部软件，此处有bug，不会显示**已经完成更新**，等待**安装**按钮变灰色后，重启下就好了

* 百度`lantern git`，安装**lantern**，在所有软件中手动找到**启动应用程序**设置lantern自动启动

* 安装chrome浏览器，直接官网下载64位deb包（注意必须先更新过软件中心后再安装软件，否则无法安装软件）

* 安装[搜狗输入法linux版](http://pinyin.sogou.com/linux/?r=pinyin)，直接官网下载64位deb包安装

* 终端打开`seahorse`，删除第一个**登录**密钥环，关闭再次打开chrome或者重启电脑打开chrome后，出现设置密码对话框后直接点击**继续**，默认密码为空，解决开机打开chrome显示需要输入秘钥的提示

**安装ubuntu16.04 unity主题包和图标**

* [主题包](http://www.noobslab.com/2016/03/ambiance-radiance-flat-colors-suite-for.html)

```
sudo add-apt-repository ppa:ravefinity-project/ppa
sudo apt-get update
sudo apt-get install ambiance-flat-colors
sudo apt-get install radiance-flat-colors
```

* [图标1](http://www.noobslab.com/2014/06/faience-and-faenza-icons-for.html)

```
sudo add-apt-repository ppa:noobslab/icons
sudo apt-get update
sudo apt-get install faenza-icon-theme
```

* [图标2](http://www.noobslab.com/2017/01/papirus-icons-updated-with-newly.html)

```
wget -qO- https://raw.githubusercontent.com/PapirusDevelopmentTeam/papirus-icon-theme/master/install-papirus-home-gtk.sh | sh
```
