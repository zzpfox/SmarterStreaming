**大牛直播 <a href="http://www.daniulive.com" target="_blank">daniulive.com</a>**

专注、极致、智慧，国内外为数不多不依赖开源框架、跨平台(windows/android/iOS)、公网推送(支持rtmp)-转发-播放(支持rtmp/rtsp)，**比快更快**，业界**真正靠谱**的超低延迟(通常1秒左右，低延迟模式下200~400ms)。

适用于**在线教育、智能可视门禁对讲、秀场直播、[超低延迟娃娃机抓取播放方案](https://github.com/daniulive/SmarterStreaming/wiki/%E8%B6%85%E4%BD%8E%E5%BB%B6%E8%BF%9F%E5%A8%83%E5%A8%83%E6%9C%BA%E6%8A%93%E5%8F%96%E6%92%AD%E6%94%BE%E6%96%B9%E6%A1%88)、媒体移动直播、[应急指挥调度](https://github.com/daniulive/SmarterStreaming/wiki/%5B%E5%BA%94%E6%80%A5%E6%8C%87%E6%8C%A5%5D%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0android%E7%BB%88%E7%AB%AF%E5%92%8Cwindows%E6%8C%87%E6%8C%A5%E4%B8%AD%E5%BF%83%E5%AE%9E%E6%97%B6%E5%AF%B9%E8%AE%B2)(针对保险、城管、交警、消防、公安等职能管理部门的单兵应急执法系统)、可视化购物、远程专家诊断、可视化巡检、(如电信/电力线路/铁路沿线/水利设施/油田/消防设施巡检)、移动视频安防监控，企业内训、金融在线直播室、微信直播、监控对接、活动现场直播、游戏直播**等场景。

[大牛直播SDK介绍PPT](http://218.25.89.108:8080/files/daniulive/%E8%A7%86%E6%B2%83%E7%A7%91%E6%8A%80-%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADSDK%E4%BB%8B%E7%BB%8D_1203.pdf)
  
  SmarterStreaming, which is an excellent and powerful cross-platform Live Streaming publisher/playback SDK, based on RTMP/RTSP protocol, developed by daniulive.

For English introduction, please [click here](https://github.com/daniulive/SmarterStreaming/wiki/English-version);

***For commercial support, please contact 89030985@qq.com***

**SmarterStreaming SDK可供个人学习之用，企业及商用需要经过授权**；

**[latest release note](https://github.com/daniulive/SmarterStreaming/wiki/release-note)**

===========================

**模块概览**

<img src="http://player.daniulive.com:8080/files/image/大牛直播SDK0914.png" alt="一张图看懂大牛直播SDK" />

- [x] [**Windows推流端-视频处理**] 屏幕/多摄像头/水印/遮挡区域多层自由合成模块；

- [x] [**Windows推流端-音频处理**] 多路混音、回音消除、噪音抑制、自动增益、VAD检测模块；

- [x] [**Windows推流端-导播**] 数据源：1. rtmp/rtsp音视频流；2. 本地屏幕/摄像头/音频数据；3.本地flv文件；**多路流合成一路**实时导播推送；

- [x] [**Windows推流端-连麦**] 以标准协议为基础，完美支持Windows连麦；

- [x] [**Windows多路流媒体转发模块**] 支持同时**多路拉取rtmp/rtsp流/本地flv文件，并分别转发到服务器**；

- [x] [**Windows推流端**] rtmp推送模块(支持同时推多路url)；

- [x] [**Windows推流端**] 实时**录像**模块/实时**快照**功能；

- [x] [**Window直播播放器**] rtmp/rtsp超低延迟直播播放器，**播放和录像完全分离**，支持**直接拉流录像**;

- [x] [**Window点播播放器**] 支持本地flv文件播放 [使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8windows%E6%92%AD%E6%94%BE%E5%99%A8%E6%92%AD%E6%94%BE%E6%9C%AC%E5%9C%B0flv%E6%96%87%E4%BB%B6);

- [x] [**Window互动**] Windows一对一互动(可windows与windows/android/iOS互动)；

- [x] [**Android推流端**] Android屏幕、摄像头推流/录像模块;

- [x] [**Android推流端**] Android回音消除、噪音抑制、自动增益、VAD检测模块；

- [x] [**Android直播播放器**] rtmp/rtsp超低延迟直播播放器;

- [x] [**Android互动**] Android一对一互动(可android与windows/android/iOS互动)；

- [x] [**iOS推流端**] iOS摄像头推流/录像;

- [x] [**iOS直播播放器**] rtmp/rtsp超低延迟直播播放器;

- [x] [**iOS互动**] iOS一对一互动(可iOS与windows/android/iOS互动).

**本地下载**

很多开发者反应，由于项目庞大，github下载整个工程很慢，我们已经把相关demo文件和使用说明，全部上传到QQ群共享：
- [x] 大牛直播精英群: [294891451](http://shang.qq.com/wpa/qunwpa?idkey=476a9cc05db0b2924530ccbbf4fae78fa485d39418ef79c8ab71b24a8fee8a48)
- [x] 大牛直播技术交流群: [499687479](http:////shang.qq.com/wpa/qunwpa?idkey=e7686f68a39bf1b95dc2ac3b775867efc7d3cbaf3596daf6e12bc1df21e1dc59)

或者直接从私有服务器下载(Windows提供C#/C++ demo, android提供eclipse demo，iOS提供xcode demo)：

**大牛直播产品demo本地下载**

- [x] [demo测试程序] [Windows推送、播放、合成、导播、连麦Demo(32位)本地下载](http://218.25.89.108:8080/files/daniulive/windows-%E6%8E%A8%E9%80%81-%E6%92%AD%E6%94%BE%E7%89%88-2017-12-27.zip)

- [x] [demo测试程序] [Windows推送、播放、合成、导播、连麦Demo(64位)本地下载](http://218.25.89.108:8080/files/daniulive/windows-%E6%8E%A8%E9%80%81-%E6%92%AD%E6%94%BE%E7%89%88-64%E4%BD%8D-2017-12-27.zip)

- [x] [SDK demo工程代码] [Windows推流SDK(C++) Demo工程本地下载](http://player.daniulive.com:8080/files/daniulive/WIN-%E6%8E%A8%E9%80%81SDK-CPP-Demo-2017-12-22.zip)

- [x] [SDK demo工程代码] [Windows播放器SDK(C++) Demo工程本地下载](http://player.daniulive.com:8080/files/daniulive/WIN-%E6%92%AD%E6%94%BESDK-CPP-Demo-2017-12-22.zip)

- [x] [SDK demo工程代码] [Windows混流SDK(C++) Demo工程本地下载](http://player.daniulive.com:8080/files/daniulive/WIN-%E6%B7%B7%E6%B5%81SDK-CPP-Demo-2017-12-22.zip)

- [x] [SDK demo工程代码] [Windows多路流媒体转发模块SDK(C++) Demo工程本地下载](http://player.daniulive.com:8080/files/daniulive/WIN-%E8%BD%AC%E5%8F%91SDK-CPP-Demo-2017-12-22.zip)

- [x] [SDK demo工程代码] [Windows C#版本推送SDK Demo工程本地下载](http://player.daniulive.com:8080/files/daniulive/windows/WIN-%E6%8E%A8%E9%80%81SDK-C%23-Demo-2017-10-31.zip)

- [x] [SDK demo工程代码] [Windows C#版本播放SDK Demo工程本地下载](http://player.daniulive.com:8080/files/daniulive/windows/WIN-%E6%92%AD%E6%94%BESDK-C%23-Demo-2017-10-31.zip)

- [x] [SDK demo工程代码] [Windows C#多路流媒体转发模块SDK Demo工程本地下载](http://218.25.89.108:8080/files/daniulive/windows/WIN-%E8%BD%AC%E5%8F%91SDK-C%23-demo-2017-11-16.zip)

- [x] [SDK demo工程代码] [**android推送、播放、一对一互动SDK本地下载(eclipse工程)**](http://218.25.89.108:8080/files/daniulive/Daniulive-Android-SDK-2017-12-25.zip)

- [x] [SDK demo工程代码] [**iOS推送、播放SDK本地下载**](http://218.25.89.108:8080/files/daniulive/Daniulive-iOS-SDK-2017-12-22.zip)

- [x] [SDK demo扩展工程代码] [android推送、播放SDK本地下载(android studio demo工程)](http://218.25.89.108:8080/files/daniulive/Daniulive-AndroidStudio-SDK-2017-11-20.zip)

- [x] [SDK demo扩展工程代码] [Android美颜demo本地下载](http://player.daniulive.com:8080/files/daniulive/Daniulive-Android-Beauty-SmartPublisher-20170123.zip)

- [x] [SDK demo扩展工程代码] [Android后台推送摄像头/屏幕数据demo本地下载](http://218.25.89.108:8080/files/daniulive/SmartServicePublisher.zip)

**NOTE:** android平台，eclipse工程(**android推送、播放SDK本地下载(eclipse工程)**)的SDK每次release是确保同步更新的，android其他相关demo使用的SDK，请以eclipse工程内提供的SDK为准。

**大牛直播SDK集成和调用说明**

- [x] [大牛直播Windows推流端SDK说明(C#版)](http://player.daniulive.com:8080/files/daniulive/SmartPublisherSDK%20C%23%E9%9B%86%E6%88%90%E8%AF%B4%E6%98%8E1.1.pdf)

- [x] [大牛直播Windows播放端SDK说明(C#版)](http://player.daniulive.com:8080/files/daniulive/windows/SmartPlayerSDK%20C%23%E9%9B%86%E6%88%90%E8%AF%B4%E6%98%8E1.3.pdf)

- [x] [大牛直播Android推流端SDK说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADAndroid%E6%8E%A8%E6%B5%81%E7%AB%AFSDK%E8%AF%B4%E6%98%8E)

- [x] [大牛直播Android播放端SDK说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADAndroid%E6%92%AD%E6%94%BE%E7%AB%AFSDK%E8%AF%B4%E6%98%8E)
- [x] [大牛直播iOS推流端SDK说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADiOS%E6%8E%A8%E6%B5%81%E7%AB%AFSDK%E8%AF%B4%E6%98%8E)
- [x] [大牛直播iOS播放端SDK说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADiOS%E6%92%AD%E6%94%BE%E7%AB%AFSDK%E8%AF%B4%E6%98%8E)

- [x] [**移动端SDK调用说明下载**](http://218.25.89.108:8080/files/daniulive/%E8%A7%86%E6%B2%83%E7%A7%91%E6%8A%80-%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADSDK%E8%B0%83%E7%94%A8%E8%AF%B4%E6%98%8E2.4.pdf)

**大牛直播demo使用说明**

- [x] [如何简单粗暴的测试Windows推送端和Windows播放器](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A6%82%E4%BD%95%E7%AE%80%E5%8D%95%E7%B2%97%E6%9A%B4%E7%9A%84%E6%B5%8B%E8%AF%95Windows%E6%8E%A8%E9%80%81%E7%AB%AF%E5%92%8CWindows%E6%92%AD%E6%94%BE%E5%99%A8)

- [x] [大牛直播Windows RTMP推流端使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADWindows-RTMP%E6%8E%A8%E6%B5%81%E7%AB%AF%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

- [x] [大牛直播连麦使用说明(windows windows或windows与android/iOS)](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%AD%E8%BF%9E%E9%BA%A6%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E(windows-windows%E6%88%96windows%E4%B8%8Eandroid))

- [x] [大牛直播Windows播放器使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADWindows%E6%92%AD%E6%94%BE%E5%99%A8%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

- [x] [大牛直播Android推流端使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADAndroid%E6%8E%A8%E6%B5%81%E7%AB%AF%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

- [x] [大牛直播Android后台推送摄像头、屏幕数据使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADAndroid%E5%90%8E%E5%8F%B0%E6%8E%A8%E9%80%81%E6%91%84%E5%83%8F%E5%A4%B4-%E5%B1%8F%E5%B9%95%E6%95%B0%E6%8D%AE%5D%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

- [x] [大牛直播Android播放器使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADAndroid%E6%92%AD%E6%94%BE%E5%99%A8%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

- [x] [大牛直播iOS推流端使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADiOS%E6%8E%A8%E6%B5%81%E7%AB%AF%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

- [x] [大牛直播 iOS端边推流边录像使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%AD-iOS%E7%AB%AF%E8%BE%B9%E6%8E%A8%E6%B5%81%E8%BE%B9%E5%BD%95%E5%83%8F%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

- [x] [大牛直播iOS推流端使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADiOS%E6%8E%A8%E6%B5%81%E7%AB%AF%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

- [x] [大牛直播iOS播放器使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%ADiOS%E6%92%AD%E6%94%BE%E5%99%A8%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

===========================

# 功能支持

**windows屏幕截取/摄像头推送录像**

1. 视频源相关：
- [x] [屏幕/摄像头]支持帧率、关键帧间隔、码率、编码profile、编码速度等设置；
- [x] [屏幕]支持**屏幕裁剪**，根据帧率和推送分辨率，自动推荐码流；
- [x] [摄像头]支持摄像头选择、分辨率设置、帧率设置；
- [x] [扩展数据]支持外部H.264接口输入；

2. 音频源相关
- [x] [音频]采集麦克风；
- [x] [音频]采集扬声器；
- [x] [扩展数据]AAC, Speex WB, PCMA, PCMU数据接口输入；

3. 摄像头和屏幕合成
- [x] [**摄像头和屏幕实时切换**]支持推送过程中，摄像头和屏幕互相切换，单画面显示摄像头或屏幕；
- [x] [**摄像头叠加到屏幕**] 支持摄像头按照设置坐标，叠加到屏幕指定位置，并支持实时关闭叠加层；
- [x] [**屏幕叠加到摄像头**] 支持屏幕按照设定坐标，叠加到摄像头指定位置，并支持实时关闭叠加层；

4. 水印和透明度遮挡
- [x] [**实时水印**]支持**动态水印**设置，完美支持`文字水印、实时时间水印和图片水印`；
- [x] [透明度]可以设置透明度处理（设置遮盖）；

5. 音频合成
- [x] **[音频]支持扬声器和麦克风音频混音输出(同时选择“采集扬声器”和“采集麦克风”)；**

6. 音频处理
- [x] **[音频]支持音频“端点检测（VAD）”，自适应码流，音频码流更节省；**
- [x] **[音频]支持回音消除功能（一对一功能：可通过在两台windows机器同时开启daniulive的推送和播放端demo，相互推送播放测试）；**
- [x] **[音频]支持噪音抑制功能；**
- [x] **[音频]支持自动增益控制；**

7. 音视频推送类型选择
- [x] **[视频]支持推送H.264；**
- [x] **[音频]支持推送AAC；**
- [x] **[音频]支持推送Speex；**
- [x] **[音频]支持推送PCMA/PCMU；**

8. 音视频类型、静音、快照、录像等
- [x] [音视频]支持**纯音频、纯视频、音视频**推送；
- [x] [音频]推送过程中实时静音/取消静音；
- [x] [对接服务器]完美支持自建服务器或CDN；
- [x] [录像]**录像和推送完全分离**，完美支持“边推送边录像”、“先推送、后录像”、“先录像，后推送；
- [x] [录像]支持设置录像文件前缀、录像文件大小，录像文件增加日期、时间；
- [x] [快照]支持推送或录像过程中，**随时快照**；

**Windows导播平台或多路合成、混音推流/录像**

对应“SmartMixStreamDemo.exe” [点击下载](http://218.25.89.108:8080/files/daniulive/windows-推送-播放版-2017-12-27.zip)

- [x] 支持“windows屏幕截取/摄像头推送录像”模块所有功能；
- [x] 支持拉取rtmp流；
- [x] 支持拉取rtsp流；
- [x] 支持本地采集到屏幕或摄像头数据，和远程拉取得rtmp或rtsp流做合成、混音输出；
- [x] 支持导播过程中，随时切断某一路音视频或音频；
- [x] 支持rtsp数据转rtmp推送出去；
- [x] 音频混音同时选择“采集麦克风”+“采集扬声器”。

**windows多路拉流转发模块**

对应“SmartStreamRelayDemo.exe” [点击下载](http://218.25.89.108:8080/files/daniulive/windows-推送-播放版-2017-12-27.zip)

- [x] [拉流]支持拉取rtsp流；
- [x] [拉流]支持拉取rtmp流；
- [x] [预览]支持拉取到的rtsp/rtmp随时本地预览、关闭预览；
- [x] [拉流音频调节]支持拉取的rtsp/rtmp流静音；
- [x] [转发]超低延迟转发拉取的rtsp/rtmp流到rtmp server。

**windows播放器**

- [x] 基于C++开发的低延迟低资源占用的windows cs架构的播放器（exe）；
- [x] 对外提供C++/C#双重接口；
- [x] 支持RTSP/RTMP协议封装；
- [x] 支持player端截图；
- [x] 支持player端录像（可只录像不播放，或只播放不录像，或同时）；
- [x] 支持YUV/RGB数据回调；
- [x] 支持时间戳回调；
- [x] 支持链接状态、实时下载速度统计、buffer开始、buffer比例、buffer结束状态；
- [x] 支持PCM数据回调；
- [x] 支持32bit/64bit;
- [x] 支持针对类似于娃娃机直播方案的超低延迟模式设置(公网200~400ms)。

**android推流/iOS推流**

- [x] 多分辨率选择；
- [x] 支持横竖屏推送；
- [x] `音视频`推送、`纯音频`推送、`纯视频`推送；
- [x] 支持`边采集、边录像`；
- [x] 支持rtmp推送 live|record模式设置；
- [x] 真正靠谱的录像、推流分离模式，**支持推流过程中随时开启录像，录像过程中，随时推流；**
- [x] 支持本地录像文件回放、处理；
- [x] 采集过程中，前后摄像头切换；
- [x] 提供编码前(YUV/RGB)、编码后音视频(H.264/AAC)接口对接，方便AR/VR设备调用。
- [x] android/iOS自带美颜功能；
- [x] android完美支持`文字水印、实时时间水印和图片水印`；
- [x] 支持`推送端实时静音/取消静音`；
- [x] 支持软硬编码自适应；
- [x] android支持后台service推送摄像头或屏幕(推送屏幕需要5.0+版本)；
- [x] **android支持实时传递远端PCM数据；**
- [x] 支持gop间隔、帧率、bierate、android编码profile和编码速度设置；
- [x] 支持推送端镜像设置；
- [x] [音频]android支持噪音抑制功能；
- [x] [音频]android支持自动增益控制；
- [x] [音频]android支持Speex推送；
- [x] [音频]android支持Speex编码质量设置；
- [x] [快照]支持推送或录像过程中，**随时快照**;
- [x] iOS支持裁剪模式设置；
- [x] 完美支持各个厂家CDN。

**windows播放器/android播放器/iOS播放器**

- [x] 超低延迟的rtmp播放器；
- [x] 超低延迟的rtsp播放器；
- [x] 完美支持多实例播放（同时播放多路stream，可同时支持rtmp、rtsp stream播放）；
- [x] 支持RTSP TCP/UDP模式切换；
- [x] 支持播放端，buffer设置；
- [x] 支持秒开模式；
- [x] windows双击画面进入**全屏**模式；
- [x] audio支持aac/speex/g.711；
- [x] **windows播放端sdk支持回调编码过的音视频数据到上层；**.
- [x] **android支持回调audio数据到上层（供二次处理之用）；**
- [x] **android支持回调video YUV/RGB数据到上层（供二次处理之用）；**
- [x] 支持自定义播放布局;
- [x] 音视频多种render机制;
- [x] 支持播放过程中，'实时静音/取消静音';
- [x] **支持播放url快速切换**；
- [x] android/iOS支持软硬解码，业内真正靠谱的超低延迟、低资源占用播放rtsp/rtmp 1080p+；
- [x] [快照]支持播放过程中，**随时快照**；
- [x] 支持针对类似于娃娃机直播方案的超低延迟模式设置(公网200~400ms)。

**Web播放器在线测试**

http://player.daniulive.com:8080/files/SmartPlayer1Stream/SmartPlayer.html

在输入框中，清除老的url，输入推流的url，如 rtmp://player.daniulive.com:1935/hls/stream123456（以推流端生成的URL为准）。

**windows/windows或windows/android/iOS一对一互动**

- [x] [Windows]推送过程中，选择“回音消除”和“噪音抑制”；
- [x] [android] 可以边推送边播放，demo请参见 [https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/Android/SmartEchoCancellation](https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/Android/SmartEchoCancellation)
- [x] [点击获取使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%5B%E5%BA%94%E6%80%A5%E6%8C%87%E6%8C%A5%5D%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0android%E7%BB%88%E7%AB%AF%E5%92%8Cwindows%E6%8C%87%E6%8C%A5%E4%B8%AD%E5%BF%83%E5%AE%9E%E6%97%B6%E5%AF%B9%E8%AE%B2)

**windows/windows或windows与android/iOS连麦**

完美支持标准协议的windows与windows、windows与android连麦（Windows作为主体端）。

**[多对一实时通讯]**

[点击获取使用说明](https://github.com/daniulive/SmarterStreaming/wiki/%5B%E5%BA%94%E6%80%A5%E6%8C%87%E6%8C%A5%5D%E5%A6%82%E4%BD%95%E5%AE%9E%E7%8E%B0android%E7%BB%88%E7%AB%AF%E5%92%8Cwindows%E6%8C%87%E6%8C%A5%E4%B8%AD%E5%BF%83%E5%AE%9E%E6%97%B6%E5%AF%B9%E8%AE%B2)

适用于应急指挥、公安巡检等，以移动单兵设备为采集载体，实时上传音视频数据到指挥中心，并实现指挥中心对现场的实时指导。

您可以用网页进行播放测试：<a href="http://218.25.89.108:8080/files/SmartPlayer/SmartPlayer.html" target="_blank">http://218.25.89.108:8080/files/SmartPlayer/SmartPlayer.html</a>

**[SmarterStreamServer]**

- [x] 高并发，分布式部署，支持rtmp摄像机和采集设备完美对接，提供代建服务器或整套软硬件服务器方案；
- [x] 高性能的流媒体服务器，标准rtmp输入，多种方式流输出（rtmp/hls），并同步保存采集端数据；
- [x] 支持鉴权认证、各种信息展示；
- [x] 点播服务器：满足录像文件点播需求。

## windows导播、推送端/android推流端/iOS推流端 ##

**1.  windows推送：**

<img src="http://player.daniulive.com:8080/files/daniulive/win_publisher.png" width="800" alt="Windows推送" />

**2.  windows推送/实时导播：**

<img src="http://player.daniulive.com:8080/files/image/windows/mix_publisher1.png" width="800" alt="Windows推送" />

**3. android边推送边录像(支持纯音频推送和播放)：**

<img src="http://player.daniulive.com:8080/files/daniulive/android_publisher_echocancellation.png" alt="android边推送边录像" />

**4. iOS边推送边录像(支持纯音频推送和播放)：**

<img src="http://218.25.89.108:8080/files/image/iOS_publisher.jpg" width="600" alt="iOS边推送边录像" />

<img src="http://218.25.89.108:8080/files/image/iOS_publisher_2.jpg" width="600" alt="iOS边推送边录像2" />

**5. iOS录像管理：**

<img src="http://218.25.89.108:8080/files/image/iOS_recorder.JPG" width="600" alt="iOS录像管理" />

## 播放展示 ##

**1. Windows播放器：**

<img src="http://218.25.89.108:8080/files/image/windowsplayer.jpg" width="600" alt="大牛直播Windows播放器" />

**2. Windows播放导播合成效果：**

<img src="http://player.daniulive.com:8080/files/image/windows/player1.png" width="600" alt="大牛直播Windows导播播放效果" />

**3. Android播放器：**

<img src="http://218.25.89.108:8080/files/image/android.jpg" width="600" alt="大牛直播android播放器" />

**4. iOS播放器：**

<img src="http://218.25.89.108:8080/files/image/ios_player.jpg" width="600" alt="大牛直播iOS播放器" />

**5. 海思板子（4核低端版，同时播放4路720P rtmp流）：**

<img src="http://218.25.89.108:8080/files/image/box.png" width="800" alt="海思box播放" />

## SmarterStreamServer url鉴权demo ##

<img src="http://218.25.89.108:8080/files/image/url_generate.png" width="798" alt="url生成demo" />


**[上层源码目录]**

1. android推流 SmartPublisher
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/Android/SmartPublisher

2. android推流 SmartServicePublisher(后台service推送摄像头/屏幕)
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/Android/SmartServicePublisher

3. android一对一回音消除 SmartEchoCancellation
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/Android/SmartEchoCancellation

3. android播放器 SmartPlayer:
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/Android/SmartPlayer

4. iOS推流 SmartPublisher:
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/IOS/SmartiOSPublisher

5. iOS播放器 SmartPlayer:
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/IOS/SmartiOSPlayer

**[编译注意事项]**

1. 编译时找不到 libSmartPlayerSDK.a 时，请先到 SmartiOSPlayer/SmartiOSPlayer/libs 目录, 解压libSmartPlayerSDK.zip.
* 编译时找不到 libSmartPublisherSDK.a 时，请先到 SmartiOSPublisher/SmartiOSPublisher/libs 目录, 解压libSmartPublisherSDK.zip.
* iOS 需真机调试
* 由于我们域名调整，原推送、播放 demo里面的baseURL “rtmp://daiulive.com” 调整为 "rtmp://player.daniulive.com"，各位用我们server测试时，请注意调整，原域名映射到刚上线的大牛直播网站 www.daniulive.com 
* 未授权版本，限制app-name，如果需要集成到自己工程里面调试，可以用以下名字：
 ```
android推送端：SmartPublisherSDKDemo
android后台Service推送：SmartServicePublisherSDKDemo
android一对一互动：SmartEchoCancellation
android播放器：SmartPlayerSDKDemo
iOS推送端：SmartiOSPublisher
iOS播放器：SmartiOSPlayer
 ```
* 集成到自己工程，如何改名字（以推送端为例）：

 ```
android：strings.xml：
<string name="app_name">SmartPublisherSDKDemo</string>
 ```

 ```
 iOS：Info.plist-->右键Open As-->Source Code，添加或者编辑
 <key>CFBundleName</key>	
 <string>SmartiOSPublisher</string>
 ```

## 获取更多信息 ##

商务合作：

手机：130-7210-2209

商务合作QQ：89030985
<a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=89030985&site=qq&menu=yes"><img border="0" src="http://wpa.qq.com/pa?p=2:89030985:51" alt="点我在线商务咨询" title="点我在线商务咨询"/></a> 

商务合作微信:

<img src="http://218.25.89.108:8080/files/daniulive/image/shangwu_erweima.png" width="183" alt="商务合作微信" />


技术支持QQ: 2679481035
<a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=2679481035&site=qq&menu=yes"><img border="0" src="http://wpa.qq.com/pa?p=2:2679481035:51" alt="点我在线技术咨询" title="点我在线技术咨询"/></a>

技术支持微信：

<img src="http://218.25.89.108:8080/files/daniulive/image/jishu_erweima.png" width="183" alt="技术支持微信" />

QQ群(大牛直播精英群)：[294891451](http://shang.qq.com/wpa/qunwpa?idkey=476a9cc05db0b2924530ccbbf4fae78fa485d39418ef79c8ab71b24a8fee8a48)

<img src="http://218.25.89.108:8080/files/image/erweima2.png" width="183" alt="QQ交流群" />

QQ群(大牛直播技术交流群)：[499687479](http:////shang.qq.com/wpa/qunwpa?idkey=e7686f68a39bf1b95dc2ac3b775867efc7d3cbaf3596daf6e12bc1df21e1dc59)

<img src="http://218.25.89.108:8080/files/image/erweima.png" width="183" alt="QQ交流群" />

想了解更多信息，点击 
[大牛直播十万个为什么](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%AD%E5%8D%81%E4%B8%87%E4%B8%AA%E4%B8%BA%E4%BB%80%E4%B9%88)
