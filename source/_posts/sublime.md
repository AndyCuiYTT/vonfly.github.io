---
title: sublime使用技巧-持续更新
date: 2017-02-17 20:33:48
tags: [软件使用技巧,右键快捷方式添加]
categories: 其它
---

sublime使用技巧，平时用的时候觉得不错的功能就会把它分享给大家(●'◡'●)
<!-- more -->

## sublime右键快捷方式添加
window下，开始->运行->regedit
到 HKEY_CLASSES_ROOT\*\shell目录下
新建sublime(随便你起什么名字)
再到新建好的sublime目录下新建command(固定名字)

最后的目录结构【HKEY_CLASSES_ROOT\*\shell\sublime\command】

第一个双引号是你的软件安装目录
"E:\Sublime Text 3  Build 3103 x64 Portable Cracked (2016.02.11)\sublime_text.exe" -p --remote-tab-silent "%1"

window如何查看软件安装目录，如下图说明：
![window如何查看软件安装目录](http://olixffhc0.bkt.clouddn.com/sublime2.jpg)

选中上一步建好的文件command，然后双击右边的默认，把上边的内容复制进去即可。如下图说明
![sublime1](http://olixffhc0.bkt.clouddn.com/sublime1.jpg)

随便找个文件sublime能够识别的文件，鼠标右击就可以看到刚刚添加的快捷键了，可以直接打开