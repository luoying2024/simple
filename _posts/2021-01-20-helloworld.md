---
layout: post
title: OBS直播插件及安装包下载
date: 2021-01-21 0：09发布  11:31-更新
comments: true

---
OBS即Open Broadcaster Software，它是一个**免费的开源**的**视频录制和视频实时流**软件。其有多种功能并广泛使用在**视频采集，直播**等领域。

## 下载安装
[OBS官网下载地址][1]
  [1]: https://obsproject.com/zh-cn/download


下载完成后，我们找到该文件，双击进行安装。

下面我以OBS-Studio-22.0.1-Full-Installer-x64.exe为安装实例，安装OBS-Studio-22.0.1-Full-Installer-x86.exe也是同样的一个方法。建议使用美颜软件的主播安装x86版本(即32位)，如果需要x86和x64两个版本并存时，建议安装的时候不要轻易修改安装路径。


#### 准备安装

（安装界面显示是英文，安装完毕是中文）

当我们安装出现以下界面的时候，我们需要百度“DX 修复”，或者点击上面的“是（Y）”，跳转到下载DX的网页，进行下载安装。

![描述](https://upload-images.jianshu.io/upload_images/14081052-3d8553d22cc83f54.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/461/format/webp "描述")



当我们出现这样的图时，点击“是”，去下载vc库。【如果没有出现，请忽视】

![VC](https://upload-images.jianshu.io/upload_images/14081052-948f59a2e99206de.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/475/format/webp "VC")


https://obsproject.com/visual-studio-2017-runtimes
附 VC2017运行库 地址


下载完后，直接安装，稍等一段时间后，再重新打开我们的OBS安装文件。

这时候我们只需要一直下一步就行。最后安装完成，这时候建议把“Launch OBS Studio 22.0.1”前面的勾给去掉，因为我们需要管理员运行OBS。

安装OBS-studio完毕
这时候我们在桌面找到OBS的快捷方式。右击点开，找到“属性”，找到“兼容性”，按照图中的设置进行设置。最后不要忘记点击“应用”“确定”关闭窗口。

修改OBS-studio桌面图标属性
## 设置

这个参数的设置，是根据你的电脑配置进行的设置，首先我们先去测速，建议在浏览器输入http://www.speedtest.net
去进行测速，这个网站相比其他测速，速度较为准确，当然也能去其他的能测到上行速率的测速平台或者网站也可以。（比如腾讯电脑管家，金山毒霸金山卫士均可以测到上行速率）。


**建议设置值**
![](https://upload-images.jianshu.io/upload_images/14081052-1fa51ca52ac55d23.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/693/format/webp)

直播码率建议根据上行自行设定
我们OBS界面的“设置”，分别找到输出，视频。

**OBS-studio主界面**

（点开输出模式，更换为高级，编码器：根据你的实际需求，选择合适的编码方式
*【Studio版本能识别Nbidia中高端显卡以及AMD中高端显卡。】*

**速率控制** 使用CBR固定位元率，表示你的上行网速，每一秒都以相等的速度进行编码传输。比较适合歌唱类，观影类，视频互动类，同时也适用游戏类直播；使用VBR动态位元率表示当你画面禁止时，编码和上行速率占用较少于动态，不太适用歌唱，观影，视频互动。

**比特率** 根据你的上行速率进行相应的设置。不多做说明。


**直播编码设定**
![](https://upload-images.jianshu.io/upload_images/14081052-774caad391d66728.jpg?imageMogr2/auto-orient/strip|imageView2/2/w/997/format/webp)


**直播分辨率设定**
视频： 基础分辨率：建议设置1920x1080，即显示器分辨率
【当然你可以设置别的分辨率，但是建议设置分辨率比例是16：9的，这样不会有黑边。

输出分辨率：根据参考设置，可以点击右边的小三角进行缩小分辨率输出到直播间。
*一般使用1280*720即可。也可以不更改，选择和基础分辨率一致。*

**FPS**
建议值 25-45之间，当然电脑和上行速率没问题的，可以开60。

动时停用AERO：win7系统建议勾上。Win8或win10，随意

> PS：使用显示器获取，win7的AERO勾上后不会显示出QQ聊天窗口，win8和win10勾与不勾，都会显示QQ聊天窗口
每修改一次，记得应用一次，


[[参考链接]][空白签名]
[空白签名]: https://www.jianshu.com/p/2c9bed933cc7 "OBS-Studio版本的使用教程 by空白签名"


-----
