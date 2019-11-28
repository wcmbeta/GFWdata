
个人收集整理科学上网的资料，保持更新
===================

科学上网有风险，仅用于学习研究，各工具排名不分先后，速度和稳定性也没有进行系统全面的对比，有条件的可以自行尝试比较。

客户端文件存放在client文件夹(LFS管理,其实并不方便)，可以查看相关旧版本，图片存放在image文件夹。

如地址失效，版本过旧，好的建议，参与更新（哪怕是修改排版~），欢迎 issue / pull request。

目录
-------------
  * [0.修改hosts](#0修改hosts)
  * [1.Shadowsocks(R)](#1shadowsocks系列)
  * [2.Lantern蓝灯](#2lantern蓝灯)
  * [3.v2ray](#3v2ray)
  * [4.Gfw.press大杀器](#4gfwpress大杀器)
  * [5.Brook](#5brook)
  * [6.VPN Gate](#6vpngate)
  * [7.psiphon3赛风](#7psiphon3赛风)
  * [8.freegate自由门](#8freegate自由门)
  * [9.Ultrasurf无界浏览](#9ultrasurf无界浏览)
  * [10.XX-Net](#10xxnet)
  * [11.Outline](#11outline)
  * [12.自己搭建](#自己搭建)
  * [13.免费节点](#免费节点)
  * [14.相关链接](#相关链接)
  * [15.其他](#其他)

0.修改hosts
-------------
1. [google-hosts](https://github.com/googlehosts/hosts/blob/master/hosts-files/hosts)，需要经常更新

1.Shadowsocks系列
-------------
区分原版SS和SSR，SSR版本可选择配置兼容SS

### 客户端
| 名称 |                                                   Windows                                                    |                                                                           macOS                                                                           |                                                  Andoird                                                   |
|:---:|:------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------:|
| SS  | [ss](https://github.com/shadowsocks/shadowsocks-windows/releases/latest) | [ssx-ng](https://github.com/shadowsocks/ShadowsocksX-NG/releases/latest)        | [Shadowsock.apk]，[postern.apk]|
| SSR |                              [ssr-4.7.0](https://github.com/wcmbeta/GFWdata/blob/master/client/windows/ssr/ssr-4.7.0-win.7z)                               |                                                  [ssx-ng-R8-1.4.3](https://github.com/wcmbeta/GFWdata/blob/master/client/mac/ssr/SSX-NG-R8-1.4.3.dmg)                                                   |                             [SSR-3.3.5.apk](https://github.com/wcmbeta/GFWdata/blob/master/client/android/ssr/ssr-3.3.5.apk)                             |

### iOS
iOS客户端普遍支持多种协议（ss/ssr/vmess/http(s)/socks5等），由于不可抗力因素国区下架，可以用PP助手/同步推等安装(ipa备份在client文件夹)，不要使用共享账号登录iCloud，有能力建议购买正版支持作者，国区已购买
参考[TestFlight](https://blog.wateroot.com/ios/ios-how-to-test-flight.html)。热门并还在维护的[配置规则/屏蔽广告](https://blog.wateroot.com/gfw/update-ios-surge-rule-config.html)，
支持Shortcuts（捷径）/JSBox进行脚本管理更新。
1. surge
2. shadowrocket（[在线安装](https://i.shadowrocket.org/)，Safari打开）
3. Wingy
4. potatso
5. quantumult （[在线安装](https://q.shadowrocket.org/)，Safari打开）

2.Lantern蓝灯
-------------
[官网](https://getlantern.org/)，[官方论坛](https://github.com/getlantern/forum#蓝灯lantern最新版本下载)，每个月免费500M流量

### 客户端
|   名称   |                             Windows                              |                           macOS                           |                                          Andoird                                           |
|:-------:|:----------------------------------------------------------------:|:---------------------------------------------------------:|:------------------------------------------------------------------------------------------:|
所有版本建议官网/官方论坛(github)下载

3.v2ray
-------------
v2ray是Project V项目创作的内核，也是一个模块化的代理工具包，支持多种代理协议
- [项目地址](https://github.com/v2ray/v2ray-core)
- [官网](https://www.v2ray.com/)
- [客户端](https://www.v2ray.com/ui_client/)
- [如何搭建](#自己搭建)，或按照项目readme操作

4.Gfw.press大杀器
-------------
  <del>开放注册-获取节点-下载-配置-done!</del>经2017-10之后，暂停提供免费服务
  1. 注册[传送门](https://gfw.press)
  2. 各种操作(pc端，app等工具下载，服务器搭建等)[传送门](https://gfw.press/blog/?p=2047)
  3. 未越狱iOS用户[传送门](https://blog.wateroot.com/ios/ios-use-gfw-press.html)
  4. Android用户可以尝试[postern](https://github.com/wcmbeta/GFWdata/blob/master/client/android/postern.apk)

5.Brook
-------------
Brook是一款跨平台、配置简单，易于上手的工具，需要搭建服务或者他人分享。
客户端包括:Window/Mac/Android/iOS
- [项目地址](https://github.com/txthinking/brook)，有server的搭建指引和client的下载
- [如何搭建](#自己搭建)，或按照项目readme操作

6.VPNGate
-------------
VPN Gate 免费的学术实验项目。
- [官网](http://www.vpngate.net/) 提供镜像，以及每日镜像邮件订阅，提供节点和教程。

### SoftEther VPN
这种方式windows独有，需配合客户端使用，安装-搜索公共VPN-连接。另外[MS-SSTP]协议也只适用windows，但不需要客户端
- [vpngate-client-20191128](https://download.vpngate.jp/common/cd.aspx/vpngate-client-2019.11.28-build-9727.145824.zip)

### 通用协议
适用于windows及其他设备如Mac、Android、iPhone等使用以下协议方案来使用在vpngate官网获取的节点，以下两种方式尝试了多次未能成功。
- [L2TP/IPsec]() 可以通过系统设置创建vpn连接的方式
- [OpenVPN]() 使用相应的openvpn工具连接

### OpenVPN client
一般来说，下载安装OpenVPN客户端，下载节点的配置文件 xxx-.open，然后连接。
- [windows-20191031](https://swupdate.openvpn.org/community/releases/openvpn-install-2.4.8-I602-Win7.exe)
- [mac-tunnelblick](https://tunnelblick.net/release/Latest_Tunnelblick_Stable.dmg)

7.psiphon3赛风
-------------
[网站](https://psiphon3.com)

- [windows](https://psiphon3.com/psiphon3.exe)
- [Android](https://psiphon3.com/PsiphonAndroid.apk)
- [iOS-浏览器](https://itunes.apple.com/us/app/psiphon-browser/id1193362444?ls=1&mt=8)国区下架

8.freegate自由门
-------------
- [windows-7.61-20170512](https://github.com/wcmbeta/GFWdata/blob/master/client/windows/freegate/fg761p.zip)
- <del>[Android-3.2](https://github.com/wcmbeta/GFWdata/blob/master/client/android/freegate/fgma-3.2.apk)</del> 2015年的版本，基本可以无视

9.Ultrasurf无界浏览
-------------
- [windows-16.03-201607120](https://github.com/wcmbeta/GFWdata/blob/master/client/windows/Ultrasurf/u.exe)
- [Android-4.0-20170415](https://github.com/wcmbeta/GFWdata/blob/master/client/android/Ultrasurf/um.apk)

10.XXNet
-------------
类GoAgent，启动（start）-获取ip-连接GAE proxy(即Google App Engine，自带公共ID，
也可以自己创建部署：一个id每天1G流量)，也可以使用X_tunnel(收费)，IP获取晚上比较容易，公共ID也可以看YouTube标清
[github](https://github.com/XX-net/XX-Net)
- [windows/mac](https://github.com/XX-net/XX-Net/releases/latest)
- [Android-3.6.3](https://github.com/XndroidDev/Xndroid/releases)

11.Outline
----------
谷歌母公司 Alphabet 旗下网络安全部门 Jigsaw 推出了的开源项目，依赖于 Shadowsocks 协议，
分server、client两部分，目前处于早期阶段。
[官网](https://getoutline.org/)，[github](https://github.com/Jigsaw-Code/?q=outline)

|        |                                                  macOS                                                   |                                                    Windows                                                    |                                                       Linux                                                        |                                             Android                                              |                                iOS                                 |                                        Chrome OS                                        |
|:------:|:--------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------:|:---------------------------------------------------------------------------------------:|
| server | [dmg](https://raw.githubusercontent.com/Jigsaw-Code/outline-releases/master/manager/Outline-Manager.dmg) |   [exe](https://raw.githubusercontent.com/Jigsaw-Code/outline-releases/master/manager/Outline-Manager.exe)    | [AppImage](https://raw.githubusercontent.com/Jigsaw-Code/outline-releases/master/manager/Outline-Manager.AppImage) |                                                                                                  |                                                                    |                                                                                         |
| client |                     [dmg](https://itunes.apple.com/us/app/outline-app/id1356178125)                      | [exe](https://raw.githubusercontent.com/Jigsaw-Code/outline-releases/master/client/stable/Outline-Client.exe) |                                                                                                                    | [google play](https://play.google.com/store/apps/details?id=org.outline.android.client)  [apk]() | [itunes](https://itunes.apple.com/us/app/outline-app/id1356177741) | [google play](https://play.google.com/store/apps/details?id=org.outline.android.client) |

自己搭建
-------------

### vps选择
1. [vultr](https://www.vultr.com/?ref=7773671-4F)，特价<del>2.5$仅IPv6</del>，3.5$/月，500G/月
2. [搬瓦工](https://bandwagonhost.com/aff.php?aff=39514)，$19.9/年，500G/月
3. [DigitalOcean](https://m.do.co/c/c8f5eeb85ddf)，新用户送$100/60天
4. [RamNode](http://www.ramnode.com/)

### 如何搭建
介绍的大多是一键脚本，更简单，也更友好，也可参照原项目的安装指引。
1. [Shadowsocks](https://blog.wateroot.com/linux/vultr-install-shadowsock.html)
2. [ShadowsocksR](https://blog.wateroot.com/gfw/vps-install-shadowsocksr.html)
3. [大杀器](https://gfw.press/blog/?p=21)
4. [v2ray](https://blog.wateroot.com/gfw/vultr-vps-install-v2ray.html)
5. [Brook](https://blog.wateroot.com/gfw/manage-shell-install-brook.html)

### 加速
1. [BBR](https://blog.wateroot.com/linux/linux-shadowsocks-bbr.html)
2. 锐速

免费节点
-------------

### 提供免费体验/测试节点的网站
这里仅推荐免费试用，不对其付费服务做保证。有些用户节点资源用不完或者一些站点为了增加网站的流量也会分享节点和提供试用，有的几小时修改密码，可能随时失效，不是很稳定。
而且会有一些限制，比如bt，看视频等，也有被监控的风险。对速度和安全性要求较高的建议自行搭建。

- [ishadowx.net](https://d.ishadowx.com/) - 每6小时改一次密码
- [ss8.fun](https://my.ss8.fun/) - 每4小时改一次密码
- [new-pac](https://github.com/Alvin9999/new-pac/wiki/ss%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7)
- [freess](https://do.freess.today/) - 每4小时改一次密码

相关链接
-------------
### github
反馈问题，查看代码，获取最新动态，最新版本
- [google-hosts](https://github.com/googlehosts/hosts)
- [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android)
- [shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows)
- [ShadowsocksX-NG-mac](https://github.com/shadowsocks/ShadowsocksX-NG)
- [ShadowsocksX-NG-R-mac](https://github.com/qinyuhang/ShadowsocksX-NG-R)
- [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev)
- [gfw.press](https://github.com/chinashiyu/gfw.press)
- [surge.conf/rules](https://github.com/lhie1/Rules)
- [shadowrocket.conf/rules](https://github.com/h2y/Shadowrocket-ADBlock-Rules)
- [GFWList](https://github.com/gfwlist/gfwlist)
- [v2ray](https://github.com/v2ray/v2ray-core)
- [Brook](https://github.com/txthinking/brook)

### Twitter
- [clowwindy-shadowsocks](https://twitter.com/clowwindy)
- [breakwa11-shadowsocksR](https://twitter.com/breakwa11)
- [surge](https://twitter.com/SurgeDebugger)
- [shadowrocket](https://twitter.com/ShadowrocketApp)
- [potatso](https://twitter.com/PotatsoApp)
- [wingy](https://twitter.com/HelloWingy)

其他
--------------
- 项目/客户端的最新版本和更多历史版本，在github的release页面获取
- [SS官网](https://shadowsocks.org)、SSR官网等，往往仅为社区提供介绍和下载，不销售节点，使用收费节点时注意甄别。
- 一些老牌的工具，速度不一定可观。
- [Tor](https://blog.wateroot.com/tool/internet-security-tor-browser.html)、[I2P](https://blog.wateroot.com/tool/internet-security-i2p.html)也能实现类似功能，但主要还是用在匿名安全上，速度也比较慢。
- 有限传播。

<del>早日肉翻</del>[回到顶部](#目录)
