# [XIU2/TrackersListCollection](https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md)

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square)](https://github.com/XIU2/TrackersListCollection/blob/master/LICENSE)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg?style=flat-square)](https://996.icu)
[![GitHub Star](https://img.shields.io/github/stars/XIU2/TrackersListCollection.svg?style=flat-square&label=Star)](https://github.com/XIU2/TrackersListCollection/stargazers)
[![GitHub Fork](https://img.shields.io/github/forks/XIU2/TrackersListCollection.svg?style=flat-square&label=Fork)](https://github.com/XIU2/TrackersListCollection/network/members)

每天更新！全网热门公共 BitTorrent Tracker 列表合集。  

该项目仅将全网热门的公共 Tracker 列表制作成合集方便大家使用，无需再一个个导入了~。  

[「English explanation see here - Github」](https://github.com/XIU2/TrackersListCollection/#readme)

****

### Tracker是什么？

BT 下载速度取决于 **其他下载同一资源用户的上传速度**，而用户靠 **Peer、DHT、Tracker** 获得。  

> **Peer：** 在你获得一个有效用户后才会起作用，Peer 会获取该用户客户端里的用户信息。  
> **DHT：** 相当于 Peer 的进阶，每个人都储存一部分 DHT 网络信息，需要的时候会通过该网络获得用户，然后再从该用户处获得更多的网络和用户，在连不上 Tracker 的时候很有效，但缺点是一开始是没有 DHT 网络的，必须要养一段时间（下载一些热门资源）才行。  

你 BT 下载的时候，下载的文件从哪里来？是别人下载好的文件上传给你，同时你下载好的文件上传给别人。但是如果没人来牵线搭桥 ，大家怎么知道这个文件谁下载的有？而你又要上传给谁？  

> **Tracker：** 它会追踪下载同一个资源的用户，帮助你与其他用户建立连接，让其他用户把文件上传给你（给你提供下载速度），而你又把下载好的文件上传给其他需要的人（给别人提供下载速度）。

**所以，优质的 Tracker 可以有效提高资源解析速度及下载速度。**  

> 同时，**用这些 Tracker 的人越多，大家的下载速度就越快**，建议多多推荐给他人！

***下图是使用我整理的 Tracker 列表下载BT的速度（我用的是完整列表）。***

![比特彗星效果图](https://raw.githubusercontent.com/XIU2/TrackersListCollection/master/img/zh-01.png)

****

### 更新时间：2019-10-27

*这些列表每天 6:30 自动更新：*

> 精选列表中的 Tracker 相对更加稳定，少而精。  
> 完整列表中的 Tracker 数量更多，理论上效果更好，但可能会存在少量死链。  
> **Tracker 数量并不会影响 BT 软件运行速度（经过测试没感觉出差别，BT 开始时间主要取决于 BT 热门程度），所以我更推荐使用「完整列表」，以使下载速度最大化！**

* **精选列表：**(78 个)  
[https://trackerslist.com/trackers_best.txt](https://trackerslist.com/trackers_best.txt)
* **完整列表：**(438 个)  
[https://trackerslist.com/trackers_all.txt](https://trackerslist.com/trackers_all.txt)

****

#### Aria2 格式 Tracker 地址：

为了方便使用 Aria2 的人添加 Tracker，我特地按照 Aria2 配置格式单独做了一份，跟随更新。

* **精选列表：**  
[https://trackerslist.com/trackers_best_aria2.txt](https://trackerslist.com/trackers_best_aria2.txt)
* **完整列表：**  
[https://trackerslist.com/trackers_all_aria2.txt](https://trackerslist.com/trackers_all_aria2.txt)

****

### 如何使用？

#### Aria2：

复制 Aria2 格式的 Tracker 文件中内容后，粘贴到 `aria2.conf` 配置文件中的 `bt-tracker=` 后面，示例如下：
``` ini
bt-tracker=http://xxx.xx:80/announce,udp://yyy.yy:80/announce
```
> **注意：** 粘贴前请先删除旧 Tracker 内容，避免格式错误！

****

#### 比特彗星(BitComet)：

*比特彗星全功能豪华解锁版下载地址(已配置 Tracker)：[https://www.lanzous.com/b073c7g4f](https://www.lanzous.com/b073c7g4f)*   

* **工具 - 选项 - Tracker**  
**勾选两个选项** 并在最下方输入框填写 Tracker URL，然后点击 **\[立即更新\]** 按钮后，上面的大输入框就会显示获取的 Tracker 了。（如下图所示）  
> 另外说明一下，比特彗星的 **黄灯 绿灯** 仅仅影响上传速度，不影响下载速度，绿灯的前提条件就是 **公网IP** ，然后设置好 **端口映射(UPnP)** 就行了。  

![比特彗星 Tracker](https://raw.githubusercontent.com/XIU2/TrackersListCollection/master/img/zh-03.png)

****

#### qBittorrent：

* **选项[齿轮图标] - BitTorrent**  
**勾选下图红框内的选项** 并复制所有 Tracker 后粘贴到下方输入框中，然后点击 **\[Apply\]** 保存。（如下图所示）  

![qBittorrent Tracker](https://raw.githubusercontent.com/XIU2/TrackersListCollection/master/img/zh-05.png)

****

### 为什么下载速度慢？

BT 下载速度取决于资源热度。  

资源热度具体来说就是同一资源的 **当前下载人数** 及 **已下载并正在做种(上传)的人数。**  

如果一个资源没人提供上传，你就会完全没有下载速度，下载速度取决于上传的人数。   

而 Tracker 的作用就是更快的找到其他下载同一资源的用户，并帮助你们之间建立链接，起到提高 BT 下载速度的效果。

> 不仅仅是数量，还有质量，国内绝大部分人都没有公网IP，所以上传速度捉急\[没有公网IP仅影响上传速度不影响下载速度\]，只能依靠少量有公网IP的人来提供主要下载速度，这也是为什么国内BT环境这么差的主要原因，另一方面也是奸商运营商上传不对等，除此之外还老是限制BT。  

除了迅雷这种把下载过的资源缓存到自己服务器上来实现“加速”的 BT软件，其他的 BT 软件都是单纯靠其他用户给你提供下载速度。  

> 除此之外，之所以叫吸血雷，是因为迅雷会获取其他用户提供给你的下载速度，但却只把你上传的数据提供给其他迅雷用户，而不是其他客户端的用户，所以对于其他客户端来说，就是迅雷只进不出，俗称吸血雷。  

***更多的请看这篇文章：[https://zhuanlan.zhihu.com/p/87193566](https://zhuanlan.zhihu.com/p/87193566)***

****

### Tracker来源

该项目汇集了以下公共跟踪器列表：
* [https://github.com/ngosang/trackerslist](https://github.com/ngosang/trackerslist)
* [https://newtrackon.com/list](https://newtrackon.com/list)
* [https://torrents.io/tracker-list/](https://torrents.io/tracker-list/)
* [http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt](http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt)
* [https://tinytorrent.net/best-torrent-tracker-list-updated/](https://tinytorrent.net/best-torrent-tracker-list-updated/)
* [https://torrenttrackerss.com/torrent-tracker-list/](https://torrenttrackerss.com/torrent-tracker-list/)
* [http://www.torrenttrackerlist.com/torrent-tracker-list](http://www.torrenttrackerlist.com/torrent-tracker-list)

感谢这些项目！

****

### 帮助项目

* 您知道更多公共追踪器列表吗？(例如: ngosang/trackerslist) => [Open a new issue](https://github.com/XIU2/TrackersListCollection/issues/new)

****

### 许可证
The GPL-3.0 License.  
The Anti-996 License.
