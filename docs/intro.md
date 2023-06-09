# 快速入门

就让我们用5分钟的时间快速了解一下HUAWEI HiCar（后续为表述方便，我们将其简称为HiCar）。

## 1.HiCar是什么
HiCar是华为提供的手机、车机互联方案，将手机和车机连接后，可以在车机系统中直接使用手机中的应用，例如导航、音乐等应用。
<img
  src={require('./img/hicar.png').default}
  width="800" 
/>

## 2.HiCar能做什么

### 导航
您可以在车机上直接使用安装在手机中的地图应用，例如高德地图、百度地图、花瓣地图等。
<img
  src={require('./img/navigation.png').default}
  width="800" 
/>

### 听歌
您可以在车机上直接使用安装在手机中的音频应用，例如网易云音乐、QQ音乐、贝瓦儿歌、腾讯新闻等。
<img
  src={require('./img/music.png').default}
  width="800" 
/>

### 打电话
您可以在车机上直接使用手机上的电话应用拨打电话。
<img
  src={require('./img/call.png').default}
  width="800" 
/>

### 看视频
您可以在驾车休息期间在车机上直接使用手机上的视频应用观看喜爱的视频节目。
<img
  src={require('./img/video.png').default}
  width="800" 
/>

### 控制车内设备

如果您购买了支持HiCar的车载香薰和智能儿童安全座椅，那您就可以直接通过HiCar控制它们。

<img
  src={require('./img/aromatherapy-card.png').default}
  width="800" 
/>

<img
  src={require('./img/aromatherapy-ui.png').default}
  width="800" 
/>

### 语音控制

如果您觉得驾驶期间操作车机屏幕并不方便和安全，那您可以直接通过语音的方式，几乎可以完成上述所有功能。
<img
  src={require('./img/voice.png').default}
  width="800" 
/>

### 更多功能

HiCar还支持车内畅连视频，例如畅连视频到您家中的智慧屏，与您的家人一同分享行车中的美景。

HiCar还支持智慧生活中设置“回家”、“离家”场景后，直接在车机屏幕上远程控制家中的智能设备。

更多HiCar支持的功能等您亲自探索。

## 3.HiCar包含哪些部分

HiCar是个比较复杂的软件解决方案，涉及到手机侧和车机侧的应用层和系统层。由于涉及到系统底层的部分能力，所以无论在手机侧还是车机侧，是无法简单通过在手机侧和车机侧安装软件的方式，让原本不支持HiCar的手机或车机支持HiCar。

<img
  src={require('./img/arts.png').default}
  width="800" 
/>

### 手机侧

首先，在手机侧，我们最直观看到的就是手机上会有一个HiCar App，也就是我们网站首页直接下载的那些Apks。

其次，比较反直觉的一点是，连接HiCar后，在车上看到的HiCar里面的高德地图、网易云音乐等应用，并不需要安装在车机上，而是安装在手机上。

然后，手机系统的部分，我们往往无法直接感知，HiCar正常运行，必须依赖手机底层系统的部分能力。所以，并不是任何手机都可以支持HiCar。

### 车机侧

车机侧的存在感比较低，它主要的功能就是在车机侧打通与手机侧连接的通道，为手机提供使用车机屏幕、音响等硬件的方法。


我们后续会在其他章节会较为深入的解释HiCar的技术架构，敬请期待。

## 4.如何使用HiCar

想使用HiCar简单一句话就是：使用支持HiCar的手机连上支持HiCar的车使用支持HiCar的应用。

这其中有三个条件：

首先，支持HiCar的应用，比较好获取，只要了解到是哪些应用支持HiCar，前往应用市场下载安装到手机即可。这部分我们在后面的章节也有提到，详情在[获取应用](./guides/app/obtain.md)。

其次，支持HiCar的手机，主要是部分华为、荣耀以及部分华为智选的机型，具体如何判断您的手机是否支持HiCar，详情在[检查手机](/check/phone.md)。

然后，支持HiCar的车型，这里相对手机而言会复杂一些，有部分新车原车就支持HiCar，存量的老车可以通过盒子方案使用HiCar，也可以通过后装的车机、车载智慧屏或智能后视镜使用HiCar，这部分的详情在[检查车辆](./check/car.md)。


到这里，您应该对HiCar有了初步的理解，后续的章节，我们也将会从HiCar的各个方面逐一展开，进行更广泛、更深入的介绍和说明。
