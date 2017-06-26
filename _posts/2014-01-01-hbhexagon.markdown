---
layout: post
title: HBHexagon
date: 2014-01-01 00:00:01 -08:00
---
`4th Jun 2015`

![](assets/images/hbhexagon/icon.png)

<center>
<h1>
<a href="https://github.com/billhu1996/HBHexagon/" class="fa fa-github"></a>
</h1>
</center>

`HBHexagon` 是一个为十分简单的东西, 他只解决一个问题, 为图片添加六边形蒙版. 这个问题正常情况下几乎不会遇到, 但是在做一个项目时需要这样的一个VIP头像. 

`项目描述` 图片的六边形蒙版, 除了圆形, 产品经理也跟我要过六边形的, 所以嘛...

`主要功能实现` 扩展UIImage, 使用CGContext画出六边形框架, 通过UIGraphics相关方法剪裁图像.