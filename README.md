<h1> EasyDSS高性能流媒体服务器 </h1>

## EasyDSS简介 ##

EasyDSS商用流媒体服务器是EasyDarwin流媒体团队开发的一款支持视频点播、转码、RTMP推流直播、RTMP/HLS直播分发、服务端录像、录像检索、录像下载、时移回放的商用流媒体服务器，采用业界优秀的流媒体框架模式设计，服务运行高效、稳定、可靠、易维护，支持RTMP直播、RTMP推送、HTTP点播、HLS直播，并支持关键帧缓冲，画面秒开等多种特性，能够接入WEB、Android、iOS、微信等全平台客户端，是移动互联网时代贴近企业点播/直播需求的一款接地气的流媒体服务器，配套OBS、EasyRTMP等直播推流工具以及EasyPlayer等网络播放器，可以形成一套完整的视频直播、录播解决方案，满足用户在各种行业场景的流媒体业务需求。

## 功能特点 ##

1. 接收RTMP推流：EasyDSS能够接收RTMP推流客户端推送的RTMP音视频流(H264+AAC)，并转发给播放客户端；
1. 分发RTMP流：EasyDSS提供RTMP流的高性能分发，RTMP播放客户端可直接连接EasyDSS进行播放；
1. 分发HLS流：EasyDSS提供同步输出HLS流的功能，可以将推送的RTMP流进行实时HLS切片，并提供HLS流的高性能分发；
1. 直播录像：支持将推送的直播流进行同步录像保存；
1. 直播录像检索：支持检索系统的直播录像，提供录像检索和列表接口；
1. 直播录像回放点播：可以点播录制的服务端录像，提供HLS点播，自由seek与倍数播放功能；
1. 录像下载：可以对检索到的录像段进行下载，另存为MP4文件；
1. HTTP服务器：EasyDSS同时也是一款高性能的HTTP服务器，用于提供HTTP访问，同时用于HLS流分发（具备nginx所有属性功能）；
1. 防盗链：持HTTP防盗链技术；
1. 主动拉取RTMP流进行转发：EasyDSS支持对RTMP流的主动拉取，并将此RTMP流进行RTMP/HLS的转发；
1. 转发RTMP流推送：支持将推送客户端推送的RTMP流，转发推送到其他RTMP流媒体服务器；
1. 推流鉴权验证：支持对推送客户端的推送流进行推流验证，若无权限的推流地址，则不接收客户端推流；
1. 推流信息统计：可以对推送流进行信息统计，包括推送时长、观看人数、起始时间、持续时长、视频码率、音频码率、推送流量等信息；
1. 播放鉴权：支持播放客户端播放验证，无权限的播放地址将无法进行播放；
1. 播放信息统计：可以对播放客户端的数量进行统计，并且可以统计客户端的开始时间、播放时长、播放流量等信息；
1. 视频文件点播：支持点播HLS/mp4文件；
1. 跨平台：支持多种平台部署运行，Windows、Linux；
1. 二次开发：提供HTTP二次开发接口，可使用接口进行一定的二次开发；

## EasyDSS生态 ##

- EasyDSS-Solution

- EasyNVR

- EasyRMS

## 技术支持 ##

- 邮件：[support@easydarwin.org](mailto:support@easydarwin.org) 

- Tel：13718530929

- QQ交流群：[538316953](https://jq.qq.com/?_wv=1027&k=5ovcEOi "EasyDSS")

> **我们同时提供Windows、Linux版本的EasyDSS高性能流媒体服务器**：EasyDSS流媒体服务器商业使用需要经过授权才能永久使用，商业授权方案可以通过以上渠道进行更深入的技术与合作咨询；


## 获取更多信息 ##

**EasyDarwin**开源流媒体服务器：[www.EasyDarwin.org](http://www.easydarwin.org)

**EasyDSS**商用流媒体解决方案：[www.EasyDSS.com](http://www.easydss.com)

**EasyNVR**无插件直播方案：[www.EasyNVR.com](http://www.easynvr.com)

Copyright &copy; EasyDarwin Team 2012-2018

![EasyDarwin](http://www.easydarwin.org/skin/easydarwin/images/wx_qrcode.jpg)