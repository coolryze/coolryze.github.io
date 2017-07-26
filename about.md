---
layout: page 
title: About

---
## 联系方式
- 手机：13716811077
- Email：ryzehe@gmail.com


## 个人信息
- 何雨泽 / 男 / 1994
- 本科 / 软件工程 / 成都东软学院（2012 ~ 2016）
- GitHub： [https://github.com/coolryze](https://github.com/coolryze)
- 个人博客：[https://coolryze.github.io](https://coolryze.github.io)
- 工作年限：2年


## 工作经历
**当果科技（北京）有限公司** *iOS小组负责人*（__2016.06 ~ 2017.06__）

**集易（北京）科技有限公司** *iOS开发工程师*（__2015.10 ~ 2016.06__）

**SOVO（校内大学生创业平台）**及 **移动开发实验室** *Java、Android、iOS开发* （__2013 ~ 2015__）


## 项目经验

#### 嘿视频 
- 嘿视频是一款街舞领域的视频社交应用。该项目是我和服务端同事离职后经朋友介绍接的一个项目，iOS 端我独立负责，开发周期总共14天，目前正上架Apple Store。
- 项目使用 Swift 3.1 和 MVVM 架构开发，涉及第三方登录与分享、视频播放、评论与回复、社交关系、推送功能。其中核心模块“视频播放”采用我发布在 GitHub 的开源框架 YZPlayer 实现，极大缩短了项目的开发周期。

#### Mity
- Mity 是一款让用户和陌生人视频聊天的社交应用，该项目是公司转型时所定的项目。iOS端共两人，我负责提供项目技术实现解决方案和项目核心模块“实时视频通话服务”和“用户匹配机制”的实现，项目开发周期为一个月，但即将上架时，公司解散，项目终止。
- 项目使用 Swift 3.0、MVVM 架构、RxSwift 函数式响应框架开发。“实时视频通话服务”通过 Google 开源框架 WebRTC 实现，“用户匹配机制”通过 Socket.IO 框架和服务端建立 Socket 长连接通信信道，用来支撑 WebRTC 的 Signaling Server 得以实现“用户匹配”及信令 offer 和 anwser 的传递。

#### Hipo热拍
- Hipo热拍是一款高清图片、短视频社交应用，类似于 Instagram。iOS端 1.0 到 2.0 版本由我独立开发，3.0 之后新加入两名同事共同迭代开发。
- 项目使用 Swift 和 MVVM 架构开发，1.0 时期使用 Swift 2.3，后续迁移至 Swift 3.0。我负责产品的功能定型、1.0 到 2.0 的全部模块、项目版本迁移、3.0 主页及发布视频和图片、性能调优。解决了主页的动态时间轴复杂布局的技术难点，包括多重回复评论展示、每条动态的高度计算与缓存、实时点赞与收藏动态内容发生变化局部刷新、实时计算滚动位置播放最接近屏幕水平中轴的视频，优化了滚动流畅度，从最初不稳定的帧率提高到稳定 60 帧。

#### MU直播
- MU直播是一个专注于影视明星的直播平台。该项目是当果科技的第一个移动产品，iOS 端由我独立开发，开发周期为 20 天。
- 项目使用 Objective-C 和 MVC 架构以及七牛云直播 SDK 进行开发。通过在“炸鸡直播”项目中得到的技术解决方案基础上进行的快速开发。通过对产品的优化提高了直播间整体性能，还在 iOS 端通过双重缓存策略优化了直播间的礼物展示规则，提高了礼物展示逻辑的正确性。

#### 炸鸡直播
- 炸鸡直播是一款当时移动互联网正处在“直播热”时开发的项目，iOS 端由我和一名 iOS 实习生进行开发，项目周期为一个半月。
- 项目使用 Objective-C 和 MVC 架构以及七牛云直播 SDK 进行开发。项目包括第三方登录与分享、直播、定位、内购、推送、即时通讯。我负责项目搭建、框架选择、直播间、即时通讯模块的开发。直播间推流与观看采用七牛云 SDK，直播间群聊功能使用融云聊天室，礼物、弹幕使用 Socket.IO 框架与服务端建立长连接进行通信。


## 技术能力
(注：以下所列技术，除非特殊说明，熟练度都为`掌握`，即能够在项目开发中使用，并了解底层实现)

- `开发语言`：		C, Objective-C, Swift
- `架构模式`：		MVC, MVVM
- `GUI`：			Cocoa Touch, AutoLayout, Interface Builder
- `网络 & 多线程`：	HTTP & HTTPS, Socket, XML & JSON 解析, NSURLSession / AFNetWorking / SnapKit, GCD / NSOperation, RunLoop
- `动画 & 绘图`：	Core Animation, Core Graphics
- `音视频`：			AVFoundation / AVKit
- `定位 & 地图`：	Core Location, MapKit / BaiduMapKit
- `存储技术`：		SQLite, FMDB, Core Data
- `版本管理`：		SVN, Git
- `其他`：			内存管理, Runtime, Instrument 工具, 视频聊天, 即时通讯, 远程推送, 移动支付等


## 开源项目
> [YZPlayer](https://github.com/coolryze/YZPlayer)：使用 Swift 语言，基于 AVPlayer 的视频播放器。支持横竖屏切换，播放进度、音量、屏幕亮度的调整，支持手势操作和重力感应。简单、易用，持续更新至 Swift 3.1。

> [YZFloatAnimation](https://github.com/coolryze/YZFloatAnimation)：使用 Core Animation 实现的漂浮动画，具有 Objective-C、Swift 双语版本，使用简单，快速集成。