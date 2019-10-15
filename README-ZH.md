# XIU2/TrackersListCollection

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square)](https://github.com/XIU2/TrackersListCollection/blob/master/LICENSE)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg?style=flat-square)](https://996.icu)

每天更新！全网热门公共 BitTorrent Tracker 列表合集。  

该项目仅将全网热门的公共 Tracker 列表制作成合集方便大家使用，无需再一个个导入了~。  

[English explanation see here](https://github.com/XIU2/TrackersListCollection/blob/master/README.md)

****

### Tracker是什么？

Tracker 是 BT 下载中一个必须的角色。  

你 BT 下载的时候，下载的文件从哪里来？是别人下载好的文件上传给你，同时你下载好的文件上传给别人。但是如果没人来牵线搭桥 ，大家怎么知道这个文件谁下载的有？而你又要上传给谁？  

Tracker 就起到这个作用，它会追踪有多少人在下载同一个文件，并把这些用户的名单发送给你的 BT下载软件，BT下载软件就会尝试链接这些用户，让已下载该文件的用户上传给你（给你提供下载速度），而你把下载好的上传给正在下载这个文件的人（给别人提供下载速度）。  

**所以，优质的 Tracker，可以有效提高资源解析速度及下载速度。** 同时，**用这些 Tracker 的人越多，大家的下载速度就越快**，所以请多多给身边的朋友推荐！（用的人越多给你提供下载速度的人就越多）  

***下图是使用我整理的 Tracker 列表下载BT的速度（我用的是完整列表）。***

![比特彗星效果图](https://github.com/XIU2/TrackersListCollection/raw/master/img/zh-04.png)

****

### 更新时间：2019-10-12

*这些列表每天 6:30 自动更新：*

> 精选列表中的 Tracker 相对更加稳定，少而精。  
> 完整列表中的 Tracker 数量更多，理论上效果更好，但可能会存在少量死链。  
> **Tracker 数量并不会影响 BT 软件运行速度，所以我更推荐使用【完整列表】，以使下载速度最大化！**

* **精选列表：**(72 个)  
[https://trackerslist.com/trackers_best.txt](https://trackerslist.com/trackers_best.txt)
* **完整列表：**(439 个)  
[https://trackerslist.com/trackers_all.txt](https://trackerslist.com/trackers_all.txt)

****

#### Aria2 Tracker

为了方便使用 Aria2 的人添加 Tracker，我特地按照 Aria2 配置格式单独做了一份，跟随更新。

* **精选列表：**  
[https://trackerslist.com/trackers_best_aria2.txt](https://trackerslist.com/trackers_best_aria2.txt)
* **完整列表：**  
[https://trackerslist.com/trackers_all_aria2.txt](https://trackerslist.com/trackers_all_aria2.txt)

[Aria2 使用方法](https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md#Aria2)

****

### Tracker来源？

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

### 如何使用？

#### Aria2

复制 Aria2 Tracker 后，粘贴到 `aria2.conf` 配置文件中的 `bt-tracker=` 后面，示例如下：
``` ini
bt-tracker=http://xxx.xx:80/announce,udp://yyy.yy:80/announce
```
> **注意：** 粘贴前请先删除旧 Tracker 内容，避免格式错误！

****

#### 比特彗星(BitComet)

* 步骤：**工具 - 选项 - Tracker**  
勾选两个选项并在最下方输入框填写 Tracker URL，然后点击 **\[立即更新\]** 按钮后，上面的大输入框就会显示获取的 Tracker 了。（如下图所示）

![比特彗星订阅 Tracker URL](https://github.com/XIU2/TrackersListCollection/raw/master/img/zh-03.png)

****

### 帮助项目

* 您知道更多公共追踪器列表吗？(例如: ngosang/trackerslist) => [Open a new issue](https://github.com/XIU2/TrackersListCollection/issues/new)

****

### 许可证
The GPL-3.0 License.  
The Anti-996 License.
