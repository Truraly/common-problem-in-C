# （案例）关于Visual Studio 中“scanf”输入报错的解决方法

> 本文件为一个案例，目的是用一个简单的案例帮助你了解一篇问题解决要怎么写

## 问题详述

在使用visualstudio code使用`scanf`是报错，如图

（代码，此处略）

报错提示：
![img](https://img-blog.csdnimg.cn/f8ae2ea0541e4e9a9e01f77533b250bc.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAUG9vckd1eTAx,size_20,color_FFFFFF,t_70,g_se,x_16)

## 解决方案

根据报错信息，使用`scanf_s`代替`scanf`就可以正常运行。

因为Visualstudio认为`scanf`不够安全，于是禁用了该函数，而使用`scanf_s`代替之



## 感谢帮助

CSDN: https://blog.csdn.net/PoorGuy01/article/details/122501426