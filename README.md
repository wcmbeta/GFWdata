
个人收集整理科学上网的资料，保持更新
===================

科学上网有风险，仅用于学习研究，各工具排名不分先后,速度和稳定性也没有进行系统全面的对比，有条件的可以自行尝试比较。

客户端文件存放在client文件夹，可以查看相关旧版本，图片存放在image文件夹。

如地址失效，版本过旧，好的建议，参与更新（哪怕是修改排版~），欢迎 email / issue / pull request。

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
  * [11.自己搭建](#自己搭建)
  * [12.免费节点](#免费节点)
  * [13.相关链接](#相关链接)
  * [14.其他](#其他)

0.修改hosts
-------------
1. [google-hosts](https://github.com/googlehosts/hosts/blob/master/hosts-files/hosts)，需要经常更新

1.Shadowsocks系列
-------------
区分原版SS和SSR，SSR版本可选择配置兼容SS

### 客户端
| 名称 | windows | mac | andoird |
| :---: | :---: | :---: | :---: |
| SS | [ss-4.0.8](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.0.8/Shadowsocks-4.0.8.zip) | [ss-2.6.3](/client/mac/ss/ss-2.6.3.dmg),[ssx-ng-1.7.1](https://github.com/shadowsocks/ShadowsocksX-NG/releases/download/v1.7.1/ShadowsocksX-NG.1.7.1.zip) | [Shadowsock.apk](/client/android/ss/com.github.shadowsocks.apk),[postern.apk](/client/android/postern.apk) |
| SSR | [ssr-4.7.0](/client/windows/ssr/ssr-4.7.0-win.7z) | [ssx-ng-R8-1.4.3](/client/mac/ssr/SSX-NG-R8-1.4.3.dmg) | [SSR-3.3.5.apk](/client/android/ssr/ssr-3.3.5.apk) |

### iOS 
iOS由于不可抗力因素国区下架,可以用PP助手/同步推等安装(ipa备份在client文件夹),有能力建议购买正版支持作者,国区已购买
参考[TestFlight](https://blog.wateroot.com/ios/ios-how-to-test-flight.html)。热门并还在维护的[配置规则/屏蔽广告](https://blog.wateroot.com/gfw/surge-conf-data.html)
1. surge
2. shadowrocket
3. Wingy
4. potatso 

2.Lantern蓝灯
-------------
[官网](https://getlantern.org)，[官方论坛](https://github.com/getlantern/forum#蓝灯lantern最新版本下载)，每个月免费500M流量

### 客户端 
所有版本建议官网/官方论坛(github)下载

| 名称 | windows | mac | andoird |
| :---: | :---: | :---: | :---: |
| Lantern | [windows-蓝灯.exe](/client/windows/lantern/lantern-installer.exe) | [mac-蓝灯.dmg](/client/mac/lantern/lantern-installer.dmg) | [android-蓝灯-4.4.1.apk](/client/android/lantern/org.getlantern.lantern_20180201-4.4.1.apk) |


3.v2ray
-------------
v2ray是Project V项目创作的内核，也是一个模块化的代理工具包，支持多种代理协议
- [项目地址](https://github.com/v2ray/v2ray-core)
- [官网](https://www.v2ray.com/)
- [客户端](https://www.v2ray.com/ui_client/)
- [如何搭建](#自己搭建),或者按照官网教程操作

4.Gfw.press大杀器
-------------
  <del>开放注册-获取节点-下载-配置-done!</del>经2017-10之后,暂停提供免费服务
  1. 注册[传送门](https://gfw.press)
  2. 各种操作(pc端，app等工具下载，服务器搭建等)[传送门](https://gfw.press/blog/?p=2047)
  3. 未越狱iOS用户[传送门](https://blog.wateroot.com/ios/ios-use-gfw-press.html)
  4. Android用户可以尝试[postern]((/client/android/postern.apk))

5.Brook
-------------
Brook是一款跨平台、配置简单，易于上手的工具，需要搭建服务或者他人分享。
客户端包括:Window/Mac/Android/iOS
- [项目地址](https://github.com/txthinking/brook)，有server的搭建指引和client的下载
- [如何搭建](#自己搭建)

6.VPNGate
-------------
VPN Gate 免费的学术实验项目。
- [官网](http://www.vpngate.net/) 提供镜像，以及每日镜像邮件订阅，提供节点和教程。

### 镜像站点列表 
(更新于 2018-02-24 16:53:59)
- [镜像1](http://183-180-56-72.west.ap.gmo-isp.jp:39559/cn/) (Mirror location: Japan)
- [镜像2](http://58.122.238.147:32497/cn/) (Mirror location: Korea Republic of)
- [镜像3](http://119.200.162.179:23001/cn/) (Mirror location: Korea Republic of)
- [镜像4](http://ngn3-ppp2459.osaka.sannet.ne.jp:28896/cn/) (Mirror location: Japan)
- [镜像5](http://110.15.239.69:53209/cn/) (Mirror location: Korea Republic of)

### SoftEther VPN（推荐）
这种方式windows独有，需配合客户端使用，安装-搜索公共VPN-连接。另外[MS-SSTP]协议也只适用windows，但不需要客户端
- [windows-2018.02.24](/client/windows/vpngate/vpngate-client-2018.02.24-build-9656.140690.zip)

### 通用协议
适用于windows及其他设备如Mac、Android、iPhone等使用以下协议方案来使用在vpngate官网获取的节点，以下两种方式尝试了多次未能成功。
- [L2TP/IPsec]() 可以通过系统设置创建vpn连接的方式
- [OpenVPN]() 使用相应的openvpn工具连接

### OpenVPN client
一般来说，下载安装OpenVPN客户端，下载节点的配置文件[示例文件-.open](/conf/open-vpn/vpngate_60.128.248.155_udp_1323.ovpn)（可能已失效），然后连接。
- [windows-2017.9.26](/client/windows/open-vpn/openvpn-install-2.4.4-I601.exe)
- [mac-tunnelblick](/client/mac/open-vpn/Tunnelblick_3.7.3_build_4880.dmg)

7.psiphon3赛风
-------------
[网站](https://psiphon3.com)

- [windows](/client/windows/psiphon3/psiphon3.exe)
- [Android](/client/android/psiphon3/PsiphonAndroid.apk)
- [iOS-浏览器](https://itunes.apple.com/us/app/psiphon-browser/id1193362444?ls=1&mt=8)国区下架

8.freegate自由门
-------------
- [windows-7.61-20170512](/client/windows/freegate/fg761p.zip)
- <del>[Android-3.2](/client/android/freegate/fgma-3.2.apk)</del> 2015年的版本，基本可以无视

9.Ultrasurf无界浏览
-------------
- [windows-16.03-201607120](/client/windows/Ultrasurf/u.exe)
- [Android-4.0-20170415](/client/android/Ultrasurf/um.apk)

10.XXNet
-------------
类GoAgent，启动（start）-获取ip-连接GAE proxy(即Google App Engine，自带公共ID,也可以自己创建部署：一个id每天1G流量)，也可以使用X_tunnel(收费)，IP获取晚上比较容易，公共ID也可以看YouTube标清
[github](https://github.com/XX-net/XX-Net)
- [windows/mac](/client/xx-net/XX-Net-3.7.7.zip)
- [Android-3.6.3](/client/xx-net/android/XX-Net-3.6.3-debug.apk)

自己搭建
-------------

### vps选择
1. [vultr](http://www.vultr.com/?ref=7135423)，特价2.5$/月，500G/月
2. [搬瓦工](https://www.bwh1.net/)，$19.9/年，500G/月
3. [DigitalOcean](https://www.digitalocean.com/)
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
有些用户节点资源用不完或者一些站点为了增加网站的流量也会分享节点和提供试用，并且几小时修改密码，可能随时失效，不是很稳定，
而且会有一些限制，比如bt，看视频等，也有被监控的风险。要求较高的建议付费节点或者自行搭建。

- [ishadowx.net](https://ss.ishadowx.net/) - 每6小时改一次密码
- [ss8.fun](https://en.ss8.fun/) - 每4小时改一次密码
- [doub.io](https://doub.io/sszhfx/) - 站长和网友分享，未墙[地址](https://doub.ws)
- <del>[gfw.press](https://gfw.press) - 暂时不更新免费节点。</del>
- [new-pac](https://github.com/Alvin9999/new-pac/wiki/ss%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7)
- [free-ss](https://get.freess.today/) - 每4小时改一次密码

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
- [GFWList](https://github.com/gfwlist/gfwlist)
- [v2ray](https://github.com/v2ray/v2ray-core)
- [Brook](https://github.com/txthinking/brook)

### Twitter
- [clowwindy-shadowsocks](https://twitter.com/clowwindy)
- [breakwa11-shadowsocksR](https://twitter.com/breakwa11)
- [chinashiyu-gfw.press](https://twitter.com/chinashiyu)
- [surge](https://twitter.com/SurgeDebugger)
- [shadowrocket](https://twitter.com/ShadowrocketApp)
- [potatso](https://twitter.com/PotatsoApp)
- [wingy](https://twitter.com/HelloWingy)
 
其他
--------------
- 项目/客户端的最新版本和更多历史版本,在github的release页面获取
- SS、SSR没有所谓的什么官方网站，也不销售节点，使用收费节点注意甄别。
- 一些老牌的工具，速度不一定可观。
- [Tor](https://blog.wateroot.com/tool/internet-security-tor-browser.html)、[I2P](https://blog.wateroot.com/tool/internet-security-i2p.html)也能实现类似功能，但主要还是用在匿名安全上，速度也比较慢。
- 有限传播。
- 感谢@yanggis将owner移交回来。
 
<del>早日肉翻</del>[回到顶部](#目录)
