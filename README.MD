# orhanobut logger项目使用

开源地址：[https://github.com/open-android/Logger](https://github.com/open-android/Logger "https://github.com/open-android/Logger")

# 运行效果

![](screenshot.png)



## 使用步骤

### 1. 在project的build.gradle添加如下代码(如下图)

	allprojects {
	    repositories {
	        maven { url "https://jitpack.io" }
	    }
	}

![](screenshot2.png)

### 2. 在Module的build.gradle添加依赖

    compile 'com.github.open-android:Logger:v1.0.0'


### 3.调用Logger功能

	Logger.d("打印logger信息");//输出结果如第一张 运行效果图

	

* 详细的使用方法在DEMO里面都演示啦,如果你觉得这个库还不错,请赏我一颗star吧~~~

* 欢迎关注微信公众号

![](http://upload-images.jianshu.io/upload_images/4037105-8f737b5104dd0b5d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
	
