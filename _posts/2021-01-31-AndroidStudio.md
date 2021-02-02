# Android Studio 自安装记录

>Android Studio 的一个功能非常强大的用来做安卓开发试调的官方出品的工具。



**学习AS，上手高效安卓开发工具**

## AS安装前提

系统硬盘需要有30GB以上的空余空间，运存要足量，AS很吃CPU的，建议做好心理准备。


## AS安装流程

安装JDK-->下载AS包-->下载SDK工具-->下载SDK包并配置变量-->下载对应版本gradle包-->导入gradle包


### 安装JDK

### 下载AS包
[中文社区](http://www.android-studio.org/)

### 安装SDK

#### 下载SDK Manager
[中文社区](http://www.android-studio.org/)
[下载地址](http://www.androiddevtools.cn/)

进入页面后点击【Android SDK 】按钮，然后在弹出的选择框内点击【SDK Tools】按钮，然后界面会自动跳转到SDK 的下载界面，选择适合自己的版本进行下载，将下载后的安装包解压到相应的目录下。

进入SDK的解压目录下，双击“SDK Manager.exe”打开SDK管理器

#### 下载之前
在使用这个管理器的时候，需要使用科学上网，才能进行下载安装；或者你也可以在上面推荐的那个下载SDK的国内安卓工具网站上下载适合你的版本的Android SDK 镜像
[SDK](https://www.androiddevtools.cn/)

这里我推荐通过有Android SDK的国内镜像服务器来下载安装，这里推荐几个：
->北京化工大学镜像服务器地址：
IPv4: http://ubuntu.buct.edu.cn/  端口：`80`
IPv4: http://ubuntu.buct.cn/  端口：`80`
IPv6: http://ubuntu.buct6.edu.cn/  端口：`80`
->大连东软信息学院镜像服务器地址:
http://mirrors.neusoft.edu.cn  端口：`80`
点击菜单中的“Tools”,然后选择下拉中的“Options…”，

输入框中`HTTP Proxy Server`为`mirrors.neusoft.edu.cn`（镜像服务器的地址，注意前面不要加http）

然后填写HTTP Proxy Port为`80` （端口号）。最后在勾选下面的『Forcehttps://... sources to be fetched using http://...

配置后重新启动SDK Manager

#### 下载选择

Tools文件夹里面的Android SDK Tools（这个我们在之前的一步已经下载好了的，一般不会让你再安装了，不过有可能会让你更新），然后就是Android SDK Platform-tools和Android SDKBuild-tools，注意只需要下载最新的版本就行了。

然后就是API的选择了。我们可以看到这里提供了很多很多从Android 2.2到Android 9.x的很多版本的API，那么怎么选择呢。
新手的话，选择一个最新的版本就好了，因为Android是向下兼容的。其他的以后你要用到了在下载就行了（因为下载安装的速度实在太慢啦。。。）。所以如上图所示，这里我只选择了下载当前最新的Android 5.1.1(API 22)。这里需要说明的是，如果你以后不打算用模拟器调试，而是一直用真机来调试的话，那么就可以不用装“system images“了。

参考
![图片](https://img-blog.csdn.net/20151116193529271)

![图片](https://img-blog.csdn.net/20151116193607716)



SDK Manager在线下载安装的方式，非常漫长....



安装完成是这样子的
![安装完毕](https://img-blog.csdn.net/20151116193758466)





#### 配置环境变量
这里需要把`\platform-tools`和`\tools`路径追加到系统环境变量Path中，具体如下：

右键点击我的电脑，选择高级设置，找到点击环境变量

首先，新建一个系统环境变量，变量名为ANDROID_SDK_HOME，变量值为你的SDK安装路径

![图片](https://img-blog.csdn.net/20151116193833720)

然后在系统的Path变量后，追加`;% ANDROID_SDK_HOME%\platform-tools;% ANDROID_SDK_HOME%\tools`
![图片](https://img-blog.csdn.net/20151116193851559)

检验一下Android SDK是否安装成功：在命令行窗口中输入`adb version`

出现类似这样的提示就成功了
`C: \Users NMrHuang>adb version
Android Debug Bridge version
1.0.32`




### 安装JDK






## AS常见错误及处理




**参考引用**

[SDK配置参考](https://www.cnblogs.com/gufengchen/p/11038029.html)

