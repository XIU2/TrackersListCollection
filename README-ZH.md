# [XIU2/TrackersListCollection](https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md)

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square)](https://github.com/XIU2/TrackersListCollection/blob/master/LICENSE)
[![GitHub Star](https://img.shields.io/github/stars/XIU2/TrackersListCollection.svg?style=flat-square&label=Star)](https://github.com/XIU2/TrackersListCollection/stargazers)
[![GitHub Fork](https://img.shields.io/github/forks/XIU2/TrackersListCollection.svg?style=flat-square&label=Fork)](https://github.com/XIU2/TrackersListCollection/network/members)

每天更新！全网热门公共 BitTorrent Tracker 列表合集。  

该项目仅将全网热门的公共 Tracker 列表制作成合集方便大家使用，无需再一个个导入了~。  

> 在无法保证 Tracker 质量的情况下（毕竟大都是国内服务器，除非每天在国内测试），Tracker 数量就是来弥补质量的（数量多 相应寻找到更多用户的几率也会增加），这些全网热门 Tracker 列表项目，基本上满足了大家的需求。

> 「[English](https://github.com/XIU2/TrackersListCollection/#readme)」([trackerslist.com](https://trackerslist.com) visitors, please switch languages in the upper right corner ↗)

> **注意：** 因中国屏蔽了 Github 图片链接，导致看不到图片，请访问官网 [trackerslist.com](https://trackerslist.com)！

****

### Tracker是什么?

- ***BT 下载的文件都是其他用户上传给你的。***
- ***BT 下载速度都来自其他用户的上传速度。*** 

做种上传的用户越多，你的下载速度就越快，而用户靠 **Peer、DHT、Tracker** 获得。  

> **Peer：** 在你获得一个有效用户后才会起作用，Peer 会获取该用户客户端里的用户信息。  
> ——  
> **DHT：** 相当于 Peer 的进阶，每个人都储存一部分 DHT 网络信息，需要的时候会通过该网络获得用户，然后再从该用户处获得更多的网络和用户，在连不上 Tracker 的时候很有效，但缺点是一开始是没有 DHT 网络的，必须要养一段时间（下载一些热门资源）才行。  
> ——  
> **Tracker：** 它会追踪下载同一个资源的用户，帮助你与其他用户建立连接，让其他用户把文件上传给你（给你提供下载速度），而你又把下载好的文件上传给其他需要的人（给别人提供下载速度）。

**所以，使用 Tracker 可以帮你获取到更多的用户，而用户数量增加了，相应的也会提高下载速度。**  

> 另外，**使用这些 Tracker 的人越多，潜在用户数量就越多，大家的下载速度就越快**，所以建议多多推荐给他人！

***下图是使用我整理的 Tracker 列表下载BT的速度（我用的是完整列表）。***

![比特彗星 效果图](https://trackerslist.com/img/zh-01.png)
![qBittorrentEE 效果图](https://trackerslist.com/img/zh-07.png)

*有兴趣的可以下载 **[ubuntu-19.10.torrent](http://releases.ubuntu.com/19.10/ubuntu-19.10-desktop-amd64.iso.torrent)** 试试，该资源全球数千人做种上传，因此大部分人下载速度很快！*

****

### 更新时间: 2020-03-03

*这些列表每天自动更新：*

> 精选列表中的 Tracker 相对更加稳定，少而精。  
> 完整列表中的 Tracker 数量更多，理论上效果更好，但可能会存在少量死链。  
> **Tracker 数量并不会影响 BT 软件运行速度，因此我更推荐使用 `「完整列表」` ，以使下载速度最大化！**

* **精选列表：**(83 个)  
***https://trackerslist.com/best.txt***
* **完整列表：**(319 个)  
***https://trackerslist.com/all.txt***

****

#### Aria2 格式 Tracker 地址:

为了方便使用 Aria2 的人添加 Tracker，我特地按照 Aria2 配置格式单独做了一份，跟随更新。

* **精选列表：**  
***https://trackerslist.com/best_aria2.txt***
* **完整列表：**  
***https://trackerslist.com/all_aria2.txt***

****

### 如何使用?

#### Aria2:

复制 Aria2 格式的 Tracker 文件中内容后，粘贴到 `aria2.conf` 配置文件中的 `bt-tracker=` 后面，示例如下：
``` ini
bt-tracker=http://xxx.xx:80/announce,udp://yyy.yy:80/announce
```
> **注意：** 粘贴前请先删除旧 Tracker 内容，避免格式错误！

****

#### BitComet (比特彗星):

> ***官方网站：http://www.bitcomet.com***  
> ***便携版：https://www.lanzous.com/b073c7g4f (已配置 Tracker)***  

* **工具 - 选项 - Tracker**  
**勾选下图红框内的选项** 并填写 Tracker URL 后点击 **\[立即更新\]** 上面就会显示获取的 Tracker 了。(如下图所示)  
> 另外，比特彗星的 **黄灯 绿灯** 对下载速度影响较小，主要影响上传速度，绿灯需要 **公网IP + 端口映射(UPnP)** 。  

![比特彗星 Tracker](https://trackerslist.com/img/zh-04.png)

****

#### qBittorrent Enhanced Edition (增强版):

> ***Github：https://github.com/c0re100/qBittorrent-Enhanced-Edition***  
> ***便携版：https://www.lanzous.com/b073dnr7g (已配置 Tracker)***  

> 基于 qBittorrent 制作，增加了很多功能，例如 **订阅 Tracker URL** 功能，可以很方便的配合本项目使用。

* **选项[齿轮图标] - BitTorrent**  
**勾选下图红框内的选项** 并填写 Tracker URL 后点击 **\[Apply\]** 保存，**然后重启 qBittorrentEE 。**(如下图所示)  

![qBittorrent Enhanced Edition Tracker](https://trackerslist.com/img/zh-06.png)

****

#### qBittorrent:

> ***官方网站：https://www.qbittorrent.org***  
> ***便携版：https://www.lanzous.com/b073jjwta***  

* **选项[齿轮图标] - BitTorrent**  
**勾选下图红框内的选项** 并复制所有 Tracker 后粘贴到下方输入框中，然后点击 **\[Apply\]** 保存。(如下图所示)  

![qBittorrent Tracker](https://trackerslist.com/img/zh-05.png)

****

#### Xdown:

> ***官方网站：https://xdown.org***

* **设置 - BitTorrent设置**  
**勾选下图红框内的选项** 并填写 Tracker URL 后点击 **\[确定\]** 保存。(如下图所示) 

![Xdown Tracker](https://trackerslist.com/img/zh-08.png)

****

### 为什么一些 Tracker 连不上?

这是正常现象。  

目前网上热门的 Tracker 大都是国外服务器。  

- **一方面** 是一些国外 Tracker 服务器国内链接质量不行（丢包、速度慢、干扰等）。  
（我发现 HTTPS 的链接成功率更高，HTTP这种明文的 以及 UDP 这种经常被运营商干扰、限制的就很蛋疼了）  
- **一方面** 是一些国外 Tracker 服务器屏蔽了国内连接（迅雷丢人丢到国外了）。  
- **一方面** 是这些国外 Tracker 服务器没有你下载的资源信息。  

> 有条件的在国内手动筛选一遍会好很多（因为运营商的原因，不同地区不同运营商结果都是不同的），但太麻烦了。

况且 Tracker 数量多少不会影响 BT 软件运行的（都是多线程连接），所以也不需要在意这些连不上的，软件重试几次连不上就忽略了。

****

### 为什么下载速度慢?

BT 下载速度取决于 **其他下载同一资源的用户上传速度。**  

也就是做种的人越多（做种就是上传文件给他人），你的下载速度越快！如果一个资源没人提供上传，你就会完全没有下载速度。   

Tracker 的作用就是更快的找到下载同一资源的用户，并帮助你们之间建立链接，间接提高 BT 下载速度（前提是有人做种）。

> 不仅仅要关注用户数量，还有用户质量，国内绝大部分人都没有公网IP，所以上传速度捉急\[没有公网IP仅影响上传速度，几乎不影响下载速度\]，另一方面也是奸商运营商上传不对等，除此之外还老是限制/干扰 BT，这也是为什么国内BT环境这么差的主要原因。  

除了迅雷这种把下载过的资源缓存到自己服务器上来实现“加速”的 BT软件，其他的 BT 软件都是单纯靠其他用户给你提供下载速度。  

> 迅雷之所以叫吸血雷，是因为 **迅雷在享受其他 BT 软件用户上传提供的速度时，自身却只把上传的速度提供给其他迅雷用户，而不会提供给其他 BT 软件用户** ，所以对于其他客户端来说，迅雷只进不出，俗称吸血雷。  

![Xunlei](https://trackerslist.com/img/zh-09.png)
> 呐，刚才我做种时截的图，迅雷用户一直吸我提供的上传，而下载进度永远为 0.0%

***更详细的请看这篇文章：[https://zhuanlan.zhihu.com/p/87193566](https://zhuanlan.zhihu.com/p/87193566)***

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
* [https://github.com/DeSireFire/animeTrackerList](https://github.com/DeSireFire/animeTrackerList)

感谢这些项目！

****

### 帮助项目

* 您知道更多公共追踪器列表吗？(例如: ngosang/trackerslist) => [Open a new issue](https://github.com/XIU2/TrackersListCollection/issues/new)

****

### 许可证
The GPL-3.0 License.  
