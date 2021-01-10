# XIU2/TrackersListCollection

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square&color=4285dd)](https://github.com/XIU2/TrackersListCollection/blob/master/LICENSE)
[![GitHub Star](https://img.shields.io/github/stars/XIU2/TrackersListCollection.svg?style=flat-square&label=Star&color=4285dd)](https://github.com/XIU2/TrackersListCollection/stargazers)
[![GitHub Fork](https://img.shields.io/github/forks/XIU2/TrackersListCollection.svg?style=flat-square&label=Fork&color=4285dd)](https://github.com/XIU2/TrackersListCollection/network/members)
[![TrackersList.com](https://img.shields.io/static/v1?label=%20&message=TrackersList.com&style=flat-square&labelColor=4B93F1&color=4285dd&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAYUlEQVR42mP0nvzxPwMFgBHdgOYAbji7dsNX0g1IseeEs+cc/E68AVty+Ehyus+UT4PNAGxhEKDLiqGBYCDCYuHh+3/DzYANl38zyAsywfmwRDYIDUAGyGmD6DCgqgHEAADqpnHxT0ZWTwAAAABJRU5ErkJggg==)](https://trackerslist.com)

每天更新！全网热门 BitTorrent Tracker 列表！**觉得好用请点个[⭐](https://github.com/XIU2/TrackersListCollection/stargazers) 鼓励一下下~**   

本项目整合了全网热门 Tracker，经过层层过滤，最终得到了一个优质的 Tracker 列表方便大家使用~  

> 「[English](https://github.com/XIU2/TrackersListCollection/#readme)」([trackerslist.com](https://trackerslist.com) visitors, please switch languages in the upper right corner ↗)  

> _分享我其他的开源项目： **[一个 \[油猴脚本\] 轻松解决「Github」文件下载速度慢的问题！](https://github.com/XIU2/UserScript)**_   
> _[**CloudflareSpeedTest** - 🌩 测试 Cloudflare CDN 延迟和速度，获取最快 IP (IPv4+IPv6)！](https://github.com/XIU2/CloudflareSpeedTest)_

****

### Tracker是什么?

- _**BT 下载的文件都是其他用户上传给你的。**_
- _**BT 下载速度都来自其他用户的上传速度。**_ 

做种上传的用户越多，你的下载速度就越快，而用户靠 **Peer、DHT、Tracker** 获得。  

> **Peer：** 在获得一个有效用户后才会起作用，该用户会把它知道的用户信息告诉你。  
> **DHT：** 分布式储存用户信息，获得一个用户后，会通过该用户获得更多的用户信息。缺点是需要养（下载热门资源）。  
> **Tracker：** 记录下载同一个资源的用户信息并提供给你，帮助你与其他用户建立连接。  
> _**以上三者的优缺点是互补的，不存在谁替代谁，一起用效果最好！**_   

**使用 Tracker 可以帮你获取到更多的用户，用户数量增加了，相应的也会提高下载速度。**  

> _使用这些 Tracker 的人越多，用户数量就越多，大家的下载速度就越快，所以建议多多推荐给他人！_  

_下图是使用我整理的 Tracker 列表下载BT的速度（完整列表）。_

![BitComet](https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/zh-02.png)
![qBittorrentEE](https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/zh-03.png)

_有兴趣的可以下载 **[ubuntu-20.04.torrent](https://releases.ubuntu.com/20.04/ubuntu-20.04.1-desktop-amd64.iso.torrent)** 试试，该资源全球数千人做种上传，因此大部分人下载速度很快！_

****

### 更新时间: 2021-01-10

_以下列表每 8 小时更新一次！_

- **精选列表：**(100 个)  
 _**https://trackerslist.com/best.txt**_  
- **完整列表：**(357 个)  
 _**https://trackerslist.com/all.txt**_  
- **HTTP(S)列表：**(146 个)  
 _**https://trackerslist.com/http.txt**_  

> **备用：** 将地址中 `trackerslist.com` 替换为 `cdn.jsdelivr.net/gh/XIU2/TrackersListCollection@master`  

****

### 如何使用?

#### Aria2:

<details>
<summary>[点击展开] - 查看 Aria2 格式的 Tracker 列表</summary>

- **精选列表：**  
 **_[https://trackerslist.com/best_aria2.txt](https://trackerslist.com/best_aria2.txt)_**  
- **完整列表：**  
 **_[https://trackerslist.com/all_aria2.txt](https://trackerslist.com/all_aria2.txt)_**  
- **HTTP(S)列表：**  
 **_[https://trackerslist.com/http_aria2.txt](https://trackerslist.com/http_aria2.txt)_**  

</details>

复制 Aria2 格式 Tracker 文件中内容后，粘贴到配置文件 `aria2.conf` 中 `bt-tracker=` 的后面，示例如下：
``` ini
bt-tracker=http://xxx.xx:80/announce,udp://yyy.yy:80/announce
```
> **注意：** 粘贴前请先删除旧 Tracker 内容，避免格式错误！

****

#### BitComet (比特彗星):

> _**官方网站：http://www.bitcomet.com**_  
> _**便携版：https://xiu.lanzoux.com/b073c7g4f (已配置 Tracker，打开白屏请加入广告屏蔽白名单)**_  

* **工具 - 选项 - 任务设置 - BT下载 - Tracker**  
 **勾选下图红框内的选项** 并填写 Tracker URL 后点击 **\[立即更新\]** 上面就会显示获取的 Tracker 了。(如下图所示)  
 
> 比特彗星的 **黄灯 绿灯** 对下载速度影响较小，主要影响上传速度，绿灯需要 **公网IP + 端口映射(UPnP)** 。  

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/zh-12.png" width="50%">

****

#### qBittorrent Enhanced Edition (增强版):

> _**Github：https://github.com/c0re100/qBittorrent-Enhanced-Edition**_  
> _**便携版：https://xiu.lanzoux.com/b073dnr7g (已配置 Tracker，[开源自动化制作脚本](https://shell.xiu2.xyz/#/md/qbee_p)，打开白屏请加入广告屏蔽白名单)**_  

> 基于 qBittorrent，增加了很多实用功能，例如 **订阅 Tracker URL** ，可以很方便的配合本项目使用。

* **选项[齿轮图标] - BitTorrent**  
 **勾选下图红框内的选项** 并填写 Tracker URL 后点击 **\[Apply\]** 保存，**然后重启 qBittorrentEE 。**(如下图所示)  

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/zh-13.png" width="50%">

****

#### qBittorrent:

> _**官方网站：https://www.qbittorrent.org**_  
> _**便携版：https://xiu.lanzoux.com/b073jjwta ([开源自动化制作脚本](https://shell.xiu2.xyz/#/md/qb_p)，如打开白屏请加入广告屏蔽白名单)**_  

* **选项[齿轮图标] - BitTorrent**  
 **勾选下图红框内的选项** 并复制所有 Tracker 后粘贴到下方输入框中，然后点击 **\[Apply\]** 保存。(如下图所示)  

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/zh-05.png" width="50%">

****

#### Motrix:

> _**官方网站：https://motrix.app**_

* **选项(左下角) - 进阶设置 - Tracker 服务器 - ﹀**  
 **勾选任意一个选项（如 all.txt）** ，然后点击 **\[保存并应用\]** 保存。(如下图所示)  

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/zh-10.png" width="50%">

****

#### Xdown:

> _**官方网站：https://xdown.org**_

* **设置 - BitTorrent设置**  
 **勾选下图红框内的选项** 并填写 Tracker URL 后点击 **\[确定\]** 保存。(如下图所示) 

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/zh-08.png" width="50%">

****

### 为什么一些 Tracker 连不上?

这是正常现象。  

目前网上热门的 Tracker 大都是国外服务器。  

- **一方面** 是一些国外 Tracker 服务器国内链接质量不行（丢包、速度慢、干扰等）。  
（我发现 HTTPS 的链接成功率更高，HTTP、UDP这种明文的经常被运营商干扰、限制的就很蛋疼了）  
- **一方面** 是一些国外 Tracker 服务器屏蔽了国内连接（迅雷丢人丢到国外了）。  
- **一方面** 是这些国外 Tracker 服务器没有你下载的资源信息。  

> 有条件的在国内手动筛选一遍会好很多（但不同地区、不同运营商结果会存在差异），但太麻烦了。

况且 Tracker 数量不会影响 BT 软件运行的（多线程）重试几次连不上就会忽略了，所以也不需要在意。

****

### 为什么下载速度慢?

BT 下载速度取决于 **其他下载同一资源的用户上传速度。**  

做种的人越多（做种就是上传文件给他人），你的下载速度越快！如果一个资源没人做种，你就没有下载速度。   

Tracker 可以帮你找到更多的用户，并帮助你们之间建立链接，链接到的用户越多！下载速度就越快！  

> 不仅仅要关注用户数量，还有用户质量，国内绝大部分人都没有公网IP，所以上传速度捉急，另一方面也是奸商运营商上传不对等，还老是限制/干扰 BT，这也是为什么国内BT环境这么差的主要原因之一。  

除了迅雷这种把下载过的资源缓存到自己服务器上来实现“加速”的 BT软件，其他的 BT 软件都是单纯靠其他用户给你提供下载速度。  

> 迅雷之所以叫吸血雷，是因为 **迅雷在享受其他 BT 软件用户上传提供的速度时，自身却只把上传的速度提供给其他迅雷用户，而不会提供给其他 BT 软件用户** ，所以对于其他客户端来说，迅雷只进不出，俗称吸血雷。  

![Xunlei](https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/zh-09.png)
> 呐，刚才我做种时截的图，迅雷用户一直吸我提供的上传，而下载进度永远为 0.0%

_**更详细、完整的请看这篇文章：[https://zhuanlan.zhihu.com/p/87193566](https://zhuanlan.zhihu.com/p/87193566)**_

****

### Tracker来源

该项目汇集了以下公共跟踪器列表：
* [https://github.com/ngosang/trackerslist](https://github.com/ngosang/trackerslist)
* [https://newtrackon.com/list](https://newtrackon.com/list)
* [http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt](http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt)
* [https://tinytorrent.net/best-torrent-tracker-list-updated/](https://tinytorrent.net/best-torrent-tracker-list-updated/)
* [http://www.torrenttrackerlist.com/torrent-tracker-list](http://www.torrenttrackerlist.com/torrent-tracker-list)
* [https://github.com/DeSireFire/animeTrackerList](https://github.com/DeSireFire/animeTrackerList)
* [https://www.yaozuopan.top/index.php/archives/1014/](https://www.yaozuopan.top/index.php/archives/1014/)

感谢这些项目！

****

### 帮助项目

* 您知道更好的公共追踪器列表？(例如: ngosang/trackerslist) => [Open a new issue](https://github.com/XIU2/TrackersListCollection/issues/new)

****

### 许可证
The GPL-3.0 License.  
