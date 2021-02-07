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

### Updated: 2021-02-08

_These lists are updated every 8 hours !_

- **BEST Tracker list:** (109 trackers)  
 _**https://trackerslist.com/best.txt**_  
- **ALL Tracker list:** (365 trackers)  
 _**https://trackerslist.com/all.txt**_  
- **HTTP(S) Tracker list:** (159 trackers)  
 _**https://trackerslist.com/http.txt**_  

> **Alternate:** Replace `trackerslist.com` with `cdn.jsdelivr.net/gh/XIU2/TrackersListCollection@master`  

****

### How to use?

#### Aria2:

<details>
<summary>[Click to expand] - View the tracker list in Aria2 format</summary>

- **BEST Tracker list:**  
 **_[https://trackerslist.com/best_aria2.txt](https://trackerslist.com/best_aria2.txt)_**  
- **ALL Tracker list:**  
 **_[https://trackerslist.com/all_aria2.txt](https://trackerslist.com/all_aria2.txt)_**  
- **HTTP(S) Tracker list:**  
 **_[https://trackerslist.com/http_aria2.txt](https://trackerslist.com/http_aria2.txt)_**  

</details>

After copying the contents of the Aria2 Format Tracker file, paste it into the `bt-tracker=` tail in the `aria2.conf` configuration file. Example:
``` ini
bt-tracker=http://xxx.xx:80/announce,udp://yyy.yy:80/announce
```
> **Note:** Please delete the old Tracker content before pasting to avoid formatting errors!

****

#### BitComet:  

> _**http://www.bitcomet.com**_

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-12.png" width="70%">

****

#### qBittorrent Enhanced Edition:

> _**Github: https://github.com/c0re100/qBittorrent-Enhanced-Edition**_  

> Based qBittorrent, added many useful features, such as **Subscribing to Tracker URL** , you can easily use with this project.  

After saving the settings, be sure to **restart qBittorrent Enhanced Edition.**

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-13.png" width="70%">

****

#### qBittorrent:

> _**https://www.qbittorrent.org**_

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-04.png" width="70%">

****

#### Motrix:

> _**https://motrix.app**_

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-10.png" width="70%">

****

#### Xdown:

> _**https://xdown.org**_

<img src="https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/img/en-08.png" width="70%">

****

### Tracker Source

This project brings together the following list of public trackers:
* [https://github.com/ngosang/trackerslist](https://github.com/ngosang/trackerslist)
* [https://newtrackon.com/list](https://newtrackon.com/list)
* [http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt](http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt)
* [https://tinytorrent.net/best-torrent-tracker-list-updated/](https://tinytorrent.net/best-torrent-tracker-list-updated/)
* [http://www.torrenttrackerlist.com/torrent-tracker-list](http://www.torrenttrackerlist.com/torrent-tracker-list)
* [https://github.com/DeSireFire/animeTrackerList](https://github.com/DeSireFire/animeTrackerList)
* [https://gitee.com/harvey520/www.yaozuopan.top](https://gitee.com/harvey520/www.yaozuopan.top)

Thanks for these projects!

****

### Contribute

* Do you know more public trackers list? (E.g: ngosang/trackerslist) => [Open a new issue](https://github.com/XIU2/TrackersListCollection/issues/new)

****

### License
The GPL-3.0 License.  
