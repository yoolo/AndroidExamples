AndroidExamples
===============
Android 控件的应用例子

一：Android加载图片方案
a）我们编写的应用程序都是有一定内存限制的，程序占用了过高的内存就容易出现OOM(OutOfMemory)异常
可获取APP最高占用内存
int maxMemory = (int) (Runtime.getRuntime().maxMemory() / 1024);  
Log.d("TAG", "Max memory is " + maxMemory + "KB");  
