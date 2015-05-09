# Fglass
Frosted glass（毛玻璃效果），在网上搜索了许多但是执行的效率特别的低，这个是在StackOverFlow中看到的一些简单的方法然后修改了进行了优化，在真机上可以跑出5ms的最佳成绩，Very Good。
###效果图
![](/demoimage/img1.png)
![](/demoimage/img2.png)

###使用
 1.copy ```com.zsl.fglass.utils.Fglass```到你的项目中
 2.调用
 ```java
 Fglass.blur(image, text, 2, 8);
 ```
###注意点
> 2 ：模糊度
8 ：缩放比例
我们可以使用模糊度（1-25）配合缩放比例来使用，达到计算高斯模糊的Fast

