### 一、Native应用开发框架
#### 一种轻量级的应用开发方案，由一个Activity与多个Fragment的开发框架。

- 内含仿知乎，今日头条，微信的界面框架。
- MVC设计模型
- 可快速开发原生应用
- 支持栈层查询
- 支持外部其他框架接入
- 支持 Material Design，包括DrawerLayout、NavigationView、ToolBar、RecycleView等。
- 源码：https://github.com/YoKeyword/Fragmentation

### 二、基于Apach Cordova 的Hybrid 应用开发框架
#### 一种前后端分离的开发框架。可由H5,JS,CSS组成界面应用界面，由原生端提供前端接口完成对手机设备和其他第三方框架集成，例如：前端调起手机摄像头，或者前端调起手机支付宝或微信支付等

- 可快速开发混合应用
- 可集成腾讯TBSX5内核浏览器，提高兼容性
- 支持拦截
- 完整的Cordova插件开发教程
- 可插件化构建应用，提高复用率
- 源码及教程：https://github.com/nihaohebin/CordovaPluginDevelopment_Android

### 三、AgentWeb，H5与原生混合开发
#### AgentWeb 是一个基于的 Android WebView ，极度容易使用以及功能强大的库，提供了 Android WebView 一系列的问题解决方案 ，并且轻量和极度灵活.
- 开发使用简单
- 支持JS与Native Java通信
- 支持X5接入
- 源码：https://github.com/Justson/AgentWeb

### 四、手机摄像头，IP摄像头（海康为例），USB摄像头（罗技为例）开发
#### 一个基于深度学习CNN卷积神经网络的在线人脸识别。深入了解各类摄像头研发，如何将YUV数据转成RGB565再转Bitmap位图，并涉及NDK相关开发，JNI接口编写与调用等。
- 可实时完成人脸识别
- 可实时监测人脸并通过抠图和压缩在性能上优化
- 手机摄像头源码： https://github.com/nihaohebin/FaceDetect_Thinkjoy
- IP摄像头源码：https://github.com/nihaohebin/IPCamera
- USB摄像头源码：https://github.com/nihaohebin/usbCamera

### 五、OkGo
#### 将Okhttp封装好的请求框架，包括缓存机制，doGet,doPost，上传下载等功能封装。
 - 使用方便，可按要求配置开发
 - 支持RxJava
 - 支持RxJava2
 - 支持自定义缓存策略
 - 支持下载管理
 - 支持上传管理
 - 源码：https://github.com/jeasonlzy/okhttp-OkGo
 
### 六、DesignMode
#### 常用android开发设计模型学习
 - 有详细源码样例
 - 源码：https://github.com/nihaohebin/designModel

### 常用开发框架
|   |   |
| :------------ | :------------ |
|  [fastjson](https://github.com/alibaba/fastjson) / [gson](https://github.com/google/gson)  | 常用于 json 数据解析，可结合AndroidStudio GsonFormat插件快速解析生成bean容器  | 
| [Butterknife](https://github.com/JakeWharton/butterknife)  |  常用于 UI注解，可结合AS Butterknife zelezny插件可快速开发控件注解  |
|  XmlPullParser/[dom4j](https://dom4j.github.io/) |  常用于 xml文件解析，其中dom4j为java常用解析器，XmlPullParser为androidSDK自带常用xml解析器  |
| [Glide](https://github.com/bumptech/glide) / [Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)  |   常用于图片加载，缓存。[封装](https://blog.csdn.net/bighuan/article/details/58992524) |
| [LeakCanary](https://github.com/square/leakcanary) | 常用于检测内存泄漏，优化应用内存性能。|
| [logger](https://github.com/orhanobut/logger) | 日志管理器|
| [XRecyclerView](https://github.com/XRecyclerView/XRecyclerView)|上拉刷新，下拉加载|
| [banner](https://github.com/youth5201314/banner)| 广告页轮播 |
| [android_zxing](https://github.com/yuzhiqiang1993/zxing)| android二维码扫描 |
| [permission](https://github.com/yanzhenjie/AndPermission)|权限管理工具 |
| [CircleImageView](https://github.com/hdodenhof/CircleImageView)|圆形图片控件 |
| [PictureSelect](https://github.com/LuckSiege/PictureSelector)|图片选择器 |
| [PopWindow](https://github.com/HMY314/PopWindow)|底部弹出选择控件 |
| [PullZoomView](https://github.com/Frank-Zhu/PullZoomView)|头部背景动画 |
| [WheelView](https://github.com/Bigkoo/Android-PickerView)|滚轮控件 |
| [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/README-CN.md)|android常用工具类 |
| [GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)|android视频播放 |
| [BigImageViewPager](https://github.com/SherlockGougou/BigImageViewPager)|图片浏览器 |
| [DanmakuFlameMaster](https://github.com/Bilibili/DanmakuFlameMaster)|视频弹幕框架 |
| [apkupdate](https://github.com/azhon/AppUpdate)|应用内升级工具 |
| [loadingview](https://github.com/xiaokun19931126/LoadingView)|请求耗时加载loading动画 |
| [ProgressView](https://github.com/Moosphan/Material-ProgressView)|进度条 |
| [Lighter](https://github.com/samlss/Lighter)|新手引导界面工具 |
| [EasyPhoto](https://github.com/HuanTanSheng/EasyPhotos)|图片选择工具 |
| [NetworkState](https://github.com/allenlzhang/NetworkState)|网络监控工具 |
