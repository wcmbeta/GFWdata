
个人收集整理科学上网的资料，保持更新
===================


科学上网有风险，仅用于学习研究，文件存放在client文件夹，可以查看相关旧版本，图片存放在image文件夹。如地址失效，版本过旧，欢迎issue、pull request。


目录
-------------
  * [0.修改hosts](#0修改hosts)
  * [1.Shadowsocks(R)](#1shadowsocksr)
  * [2.Lantern蓝灯](#2lantern蓝灯)
  * [3.Gfw.press大杀器](#3gfwpress大杀器)
  * [4.VPN Gate](#4vpngate)
  * [5.psiphon3赛风](#5psiphon3赛风)
  * [6.freegate自由门](#6freegate自由门)
  * [7.Ultrasurf无界浏览](#7ultrasurf无界浏览)
  * [8.XX-Net](#8xxnet)
  * [9.自己搭建](#9自己搭建)
  * [10.免费节点](#10免费节点)
  * [11.相关链接](#11相关链接)
  * [12.其他](#12其他)




0.修改hosts
-------------
1. google-hosts文件[传送门](https://github.com/txthinking/google-hosts)，需要经常更新



1.ShadowsocksR
-------------
区分原版SS和SSR，SSR版本可选择配置兼容SS

### Android
- [Shadowsock.apk](/client/android/ss/com.github.shadowsocks.apk)
- <a href="https://play.googss-nightly-4.1.3.apkle.com/store/apps/details?id=com.github.shadowsocks"><img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="48"></a>

- [SSR-3.3.5.apk](/client/android/ssr/ssr-3.3.5.apk)
- [postern.apk](/client/android/postern.apk)，界面比较那个，却是Android里的surge，支持surge.conf

### iOS 
有能力建议购买正版支持作者,国区已购买参考[TestFlight](https://blog.wateroot.com/ios/ios-how-to-test-flight.html)。热门并还在维护的[配置规则/屏蔽广告](https://blog.wateroot.com/gfw/surge-conf-data.html)
1. surge （中国区下架）  --- 同步推 
2. shadowrocket(小飞机，中国区下架) --- PP助手
3. Wingy （中国区下架）----PP助手  [App Store免费](https://itunes.apple.com/cn/app/shadowsocks-wingy-proxy-for-http-socks5-ss/id1148026741?mt=8)
4. potatso 

### Windows
- [ss-4.0.6](/client/windows/ss/ss-4.0.6.zip)
- [ssr-4.7.0](/client/windows/ssr/ssr-4.7.0-win.7z)

### Mac
SSX带有-R8后缀的支持SSR
- [ss-2.6.3](/client/mac/ss/ss-2.6.3.dmg)，不是很推荐，是比较旧的版本
- [ssx-ng-1.6.1](/client/mac/ss/SSX-NG.1.6.1.zip)，SS推荐这个
- [ssx-ng-R8-1.4.1](/client/mac/ssr/SSX-NG-R8-1.4.1.dmg)，SSR
- [ssx-ng-R8-1.4.3](/client/mac/ssr/SSX-NG-R8-1.4.3.dmg)，SSR


2.Lantern蓝灯
-------------
[官网](https://getlantern.org)，[官方论坛](https://github.com/getlantern/forum#蓝灯lantern最新版本下载)，每个月免费500M流量
### 安装包 
-  [android-蓝灯-4.2.2.apk](/client/android/lantern/lantern-4.2.2-2017-10-16.apk) 
- <a href="https://play.google.com/store/apps/details?id=org.getlantern.lantern"><img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="48"></a>
-  [windows-蓝灯.exe](/client/windows/lantern/lantern-installer.exe)
-  [mac-蓝灯.dmg](/client/mac/lantern/lantern-installer.dmg)

3.Gfw.press大杀器
-------------
  开放注册-获取节点-下载-配置-done!
  1. 注册[传送门](https://gfw.press)
  2. 各种操作(pc端，app等工具下载，服务器搭建等)[传送门](https://gfw.press/blog/?p=2047)
  3. 未越狱iOS用户[传送门](https://blog.wateroot.com/ios/ios-use-gfw-press.html)
  4. android用户可以尝试[postern]((/client/android/postern.apk))

4.VPNGate
-------------
VPN Gate 免费的学术实验项目。
- [官网](http://www.vpngate.net/) 提供镜像，以及每日镜像邮件订阅，提供节点和教程。

### SoftEther VPN（推荐）
这种方式windows独有，需配合客户端使用，安装-搜索公共VPN-连接。另外[MS-SSTP]协议也只适用windows，但不需要客户端
- [windows-2017.10.25](/client/windows/vpngate/vpngate-client-2017.10.25-build-9651.139714.zip)

### 通用协议
适用于windows及其他设备如Mac、Android、iPhone等使用以下协议方案来使用在vpngate官网获取的节点，以下两种方式尝试了多次未能成功。
- [L2TP/IPsec]() 可以通过系统设置创建vpn连接的方式
- [OpenVPN]() 使用相应的openvpn工具连接

### OpenVPN client
一般来说，下载安装OpenVPN客户端，下载节点的配置文件[示例文件-.open](/conf/open-vpn/vpngate_60.128.248.155_udp_1323.ovpn)（可能已失效），然后连接。
- [windows-2017.9.26](/client/windows/open-vpn/openvpn-install-2.4.4-I601.exe)
- [mac-tunnelblick](/client/mac/open-vpn/Tunnelblick_3.7.3_build_4880.dmg)

5.psiphon3赛风
-------------
[网站](https://psiphon3.com)

- [windows](/client/windows/psiphon3/psiphon3.exe)
- [Android](/client/android/psiphon3/PsiphonAndroid.apk)
- [iOS-浏览器](https://itunes.apple.com/us/app/psiphon-browser/id1193362444?ls=1&mt=8)国区下架

6.freegate自由门
-------------
[网站](dongtaiwang.com)
- [windows-7.61-20170512](/client/windows/freegate/fg761p.zip)
- <del>[Android-3.2](/client/android/freegate/fgma-3.2.apk)</del> 2015年的版本，基本可以无视

7.Ultrasurf无界浏览
-------------
[网站](http://www.wujieliulan.com)
- [windows-16.03-201607120](/client/windows/Ultrasurf/u.exe)
- [Android-4.0-20170415](/client/android/Ultrasurf/um.apk)

8.XXNet
-------------
类GoAgent，启动（start）-获取ip-连接GAE proxy(即Google App Engine，自带公共ID,也可以自己创建部署：一个id每天1G流量)，也可以使用X_tunnel(收费)，IP获取晚上比较容易，公共ID也可以看YouTube标清
[github](https://github.com/XX-net/XX-Net)
- [windows/mac](/client/xx-net/XX-Net-3.7.7.zip)
- [Android-3.6.3](/client/xx-net/android/XX-Net-3.6.3-debug.apk)

9.自己搭建
-------------

### vps选择
1. [vultr](http://www.vultr.com/?ref=7135423)，特价2.5$/月，500G/月
2. [搬瓦工](https://www.bwh1.net/)，$19.9/年，500G/月
3. [DigitalOcean](https://www.digitalocean.com/)
4. [RamNode](http://www.ramnode.com/)

### 如何搭建
1. [Shadowsocks](https://blog.wateroot.com/linux/vultr-install-shadowsock.html)
2. [ShadowsocksR](https://blog.wateroot.com/gfw/vps-install-shadowsocksr.html)
3. [大杀器](https://gfw.press/blog/?p=21)

### 加速
1. [BBR](https://blog.wateroot.com/linux/linux-shadowsocks-bbr.html)
2. 锐速

10.免费节点 
-------------
 
### 提供免费体验/测试节点的网站
有些用户节点资源用不完或者一些站点为了增加网站的流量也会分享节点，并且几小时修改密码，可能随时失效，不是很稳定，
而且会有一些限制，比如bt，看视频等，也有被监控的风险。要求较高的建议付费节点或者自行搭建。

- [ishadowx.com](http://ss.ishadowx.com)-每6小时改一次密码，已墙,并重定向到[ishadowx.net](https://ss.ishadowx.net/)
- [yhyhd.org](https://xsjs.yhyhd.org/free-ss)-每周改一次密码
- [doub.io](https://doub.io/sszhfx/) - 站长和网友分享，未墙[地址](https://doub.bid)
- [gfw.press](https://gfw.press)-长期免费，大杀器配套使用，建议每周查看节点更新，域名被墙,作者消失一段时间后表示，暂时不更新免费节点。

11.相关链接
-------------
### github
反馈问题，查看代码，获取最新动态，最新版本
- [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android)
- [shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows)
- [ShadowsocksX-NG-mac](https://github.com/shadowsocks/ShadowsocksX-NG)
- [ShadowsocksX-NG-R-mac](https://github.com/qinyuhang/ShadowsocksX-NG-R)
- [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev)
- [gfw.press](https://github.com/chinashiyu/gfw.press)
- [surge.conf](https://github.com/lhie1/Surge)
- [GFWList](https://github.com/gfwlist/gfwlist)
 
### Twitter
- [clowwindy-shadowsocks](https://twitter.com/clowwindy)
- [breakwa11-shadowsocksR](https://twitter.com/breakwa11)
- [chinashiyu-gfw.press](https://twitter.com/chinashiyu)
- [surge](https://twitter.com/SurgeDebugger)
- [shadowrocket](https://twitter.com/ShadowrocketApp)
- [potatso](https://twitter.com/PotatsoApp)
- [wingy](https://twitter.com/HelloWingy)
 
12.其他
--------------
- SS、SSR没有所谓的什么官方网站，也不销售节点，使用收费节点注意甄别。
- 近期大面积节点被墙，所以添加一些老牌的工具，速度不一定可观
 
<del>早日肉翻</del>[回到顶部](#目录)
