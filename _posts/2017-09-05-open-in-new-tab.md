---
layout: post
title: typecho如何设置在新窗口中打开文章链接
---

首先找到主题文件中的index.php文件（注意不是root文件夹下的那个index.php；也可以在后台模板编辑中找到相关代码）

找到以下字段的代码：

    <a itemtype="url" href="<?php $this->permalink() ?>">

将这段代码替换为：

    <a itemtype="url" href="<?php $this->permalink() ?>" target="_blank">

保存上传即可。
