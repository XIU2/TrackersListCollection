# XIU2/TrackersListCollection

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square&color=4285dd)](https://github.com/XIU2/TrackersListCollection/blob/master/LICENSE)
[![GitHub Star](https://img.shields.io/github/stars/XIU2/TrackersListCollection.svg?style=flat-square&label=Star&color=4285dd)](https://github.com/XIU2/TrackersListCollection/stargazers)
[![GitHub Fork](https://img.shields.io/github/forks/XIU2/TrackersListCollection.svg?style=flat-square&label=Fork&color=4285dd)](https://github.com/XIU2/TrackersListCollection/network/members)
[![TrackersList.com](https://img.shields.io/static/v1?label=%20&message=TrackersList.com&style=flat-square&labelColor=4B93F1&color=4285dd&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAYUlEQVR42mP0nvzxPwMFgBHdgOYAbji7dsNX0g1IseeEs+cc/E68AVty+Ehyus+UT4PNAGxhEKDLiqGBYCDCYuHh+3/DzYANl38zyAsywfmwRDYIDUAGyGmD6DCgqgHEAADqpnHxT0ZWTwAAAABJRU5ErkJggg==)](https://trackerslist.com)

Updated daily! A list of popular BitTorrent Trackers. **If you feel good, please [⭐](https://github.com/XIU2/TrackersListCollection/stargazers)!**  

Integrated the popular Tracker, after filtering, finally got a high-quality Tracker list collection ~  

> 「[简体中文](https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md)」([trackerslist.com](https://trackerslist.com) 访客，请通过右上角切换语言 ↗)  

**** 

### What is Tracker?

Tracker is a necessary role in BT download, it can effectively improve BT download speed.  

> Record user information downloading the same resource to help you establish connections with other users.  

The more people use Tracker, the faster the BT download speed, **so please recommend it to your friends!**  

_The figure below shows the BT download speed after using Tracker. (ALL Tracker list)_  

![BitComet](https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-02.png)
![qBittorrentEE](https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-07.png)

_Those who are interested can download and try **[ubuntu-20.04.torrent](https://releases.ubuntu.com/20.04/ubuntu-20.04.1-desktop-amd64.iso.torrent)** , this resource has thousands of people worldwide to provide uploads , So most people download fast!_

****

### Updated: 2020-12-23

_These lists are updated automatically daily **[(Update Log)](https://github.com/XIU2/TrackersListCollection/releases)** :_

> BEST Tracker list is relatively more stable, concise.  
> ALL Tracker list is more in number and theoretically better.  
> **The number of Tracker does not affect the operation of the BT software, so I recommend using the `ALL Tracker list` to maximize the download speed !**

- **BEST Tracker list:** (111 trackers)  
 _**https://trackerslist.com/best.txt**_  
- **ALL Tracker list:** (402 trackers)  
 _**https://trackerslist.com/all.txt**_  
- **HTTP(S) Tracker list:** (169 trackers)  
 _**https://trackerslist.com/http.txt**_  

> **Alternate:** Replace `trackerslist.com` with `cdn.jsdelivr.net/gh/XIU2/TrackersListCollection@master`  

****

#### Aria2 Format Tracker:

In order to facilitate adding Tracker to Aria2, I also made a Tracker list in Aria2 format. The update is consistent.

- **BEST Tracker list:**  
 **_[https://trackerslist.com/best_aria2.txt](https://trackerslist.com/best_aria2.txt)_**  
- **ALL Tracker list:**  
 **_[https://trackerslist.com/all_aria2.txt](https://trackerslist.com/all_aria2.txt)_**  
- **HTTP(S) Tracker list:**  
 **_[https://trackerslist.com/http_aria2.txt](https://trackerslist.com/http_aria2.txt)_**  

****

### How to use?

#### Aria2:

After copying the contents of the Aria2 Format Tracker file, paste it into the `bt-tracker=` tail in the `aria2.conf` configuration file. Example:
``` ini
bt-tracker=http://xxx.xx:80/announce,udp://yyy.yy:80/announce
```
> **Note:** Please delete the old Tracker content before pasting to avoid formatting errors!

****

#### BitComet:  

> _**http://www.bitcomet.com**_

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-12.png" width="75%">

****

#### qBittorrent Enhanced Edition:

> _**Github: https://github.com/c0re100/qBittorrent-Enhanced-Edition**_  

> Based qBittorrent, added many useful features, such as **Subscribing to Tracker URL** , you can easily use with this project.  

After saving the settings, be sure to **restart qBittorrent Enhanced Edition.**

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-13.png" width="75%">

****

#### qBittorrent:

> _**https://www.qbittorrent.org**_

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-04.png" width="75%">

****

#### Motrix:

> _**https://motrix.app**_

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-10.png" width="75%">

****

#### Xdown:

> _**https://xdown.org**_

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-08.png" width="75%">

****

### Tracker Source

This project brings together the following list of public trackers:
* [https://github.com/ngosang/trackerslist](https://github.com/ngosang/trackerslist)
* [https://newtrackon.com/list](https://newtrackon.com/list)
* [http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt](http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt)
* [https://tinytorrent.net/best-torrent-tracker-list-updated/](https://tinytorrent.net/best-torrent-tracker-list-updated/)
* [http://www.torrenttrackerlist.com/torrent-tracker-list](http://www.torrenttrackerlist.com/torrent-tracker-list)
* [https://github.com/DeSireFire/animeTrackerList](https://github.com/DeSireFire/animeTrackerList)
* [https://www.yaozuopan.top/index.php/archives/1014/](https://www.yaozuopan.top/index.php/archives/1014/)

Thanks for these projects!

****

### Contribute

* Do you know more public trackers list? (E.g: ngosang/trackerslist) => [Open a new issue](https://github.com/XIU2/TrackersListCollection/issues/new)

****

### License
The GPL-3.0 License.  
