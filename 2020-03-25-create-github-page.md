# 使用html2canvas生成图片遇到的坑

### 背景：

活动H5，需要开发一个长按保存图片的功能，我们知道在微信里面，长按一张图片，会弹窗保存或者分享的菜单。在使用htl2canvas生成图片的过程中，遇到下面的问题以及解决采用的方案。

1. logo图片模糊
   【问题描述】在H5页面有放置了一个logo图片，logo图片使用的是以@3x的尺寸输出的。但是通过html2canvas绘制出来的图片中，里面的logo依旧模糊
2. 没有生成图片
   【问题描述】
