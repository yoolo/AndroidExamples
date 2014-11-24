### AndroidExamples ###
*记录Android开发中的项目经验*

#### 一: Android加载图片方案 ####
* 我们编写的应用程序都是有一定内存限制的，程序占用了过高的内存就容易出现OOM(OutOfMemory)异常
可获取APP最高占用内存
  int maxMemory = (int) (Runtime.getRuntime().maxMemory() / 1024);  
  Log.d("TAG", "Max memory is " + maxMemory + "KB");  


----
#### 附录1 参考 ####
* [Android高效加载大图、多图解决方案，有效避免程序OOM](http://blog.csdn.net/guolin_blog/article/details/9316683)
* [Android网络通信框架Volley详解](http://blog.csdn.net/appandroid/article/details/13023327)([git source](https://android.googlesource.com/platform/frameworks/volley))

