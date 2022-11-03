# XIU2/TrackersListCollection

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square&color=4285dd&logo=github)](https://github.com/XIU2/TrackersListCollection/)
[![GitHub Star](https://img.shields.io/github/stars/XIU2/TrackersListCollection.svg?style=flat-square&label=Star&color=4285dd&logo=github)](https://github.com/XIU2/TrackersListCollection/)
[![GitHub Fork](https://img.shields.io/github/forks/XIU2/TrackersListCollection.svg?style=flat-square&label=Fork&color=4285dd&logo=github)](https://github.com/XIU2/TrackersListCollection/)
[![TrackersList.com](https://img.shields.io/static/v1?label=%20&message=TrackersList.com&style=flat-square&labelColor=4B93F1&color=4285dd&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAYUlEQVR42mP0nvzxPwMFgBHdgOYAbji7dsNX0g1IseeEs+cc/E68AVty+Ehyus+UT4PNAGxhEKDLiqGBYCDCYuHh+3/DzYANl38zyAsywfmwRDYIDUAGyGmD6DCgqgHEAADqpnHxT0ZWTwAAAABJRU5ErkJggg==)](https://trackerslist.com)

Updated daily! A list of popular BitTorrent Trackers. **If you feel good, please [⭐](https://github.com/XIU2/TrackersListCollection/stargazers)!**  

Integrated the popular Tracker, after filtering, finally got a high-quality Tracker list collection ~  

> 「[简体中文](https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md)」(位于 [trackerslist.com](https://trackerslist.com/#/zh) 的访客，可通过右上角切换语言 ↗)  

**** 

### What is Tracker?

Tracker is a necessary role in BT download, it can effectively improve BT download speed.  

> Record user information that downloads the same resource to **help you connect with other users**.  

_The figure below shows the BT download speed after using Tracker. (all.txt)_  

![BitComet](https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/img/en-01.png)
![qBittorrentEE](https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/img/en-02.png)

_You can judge whether there is a problem with the BT configuration and network by observing the download speed of [**ubuntu.torrent**](https://releases.ubuntu.com/20.04/ubuntu-20.04.4-desktop-amd64.iso.torrent). There are many users of this popular resource, and the download speed should be very fast under normal circumstances._

****

### Updated: 2022-11-03

- **BEST Tracker list:** (119 trackers)  
 _**[https://trackerslist.../best.txt](https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/best.txt)**_  
- **ALL Tracker list:** (199 trackers)  
 _**[https://trackerslist.../all.txt](https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/all.txt)**_  
- **HTTP(S) Tracker list:** (69 trackers)  
 _**[https://trackerslist.../http.txt](https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/http.txt)**_  

<details>
<summary><strong><code>[Click to expand] - View alternate address</code></strong></summary>

****

\# **The following is an example of the complete list `all.txt` (modify the file name as needed):**  

- _**https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/all.txt**_  
- _**https://fastly.jsdelivr.net/gh/XIU2/TrackersListCollection/all.txt**_  
- _**https://gcore.jsdelivr.net/gh/XIU2/TrackersListCollection/all.txt**_  
- _**https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/all.txt**_  
- _**https://raw.githubusercontent.com/XIU2/TrackersListCollection/master/all.txt**_  

</details>

****

### How to use?

#### Aria2:

<details>
<summary><strong><code>[Click to expand] - View the tracker list in Aria2 format</code> </strong></summary>

- _**[https://trackerslist.../best_aria2.txt](https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/best_aria2.txt)**_  
- _**[https://trackerslist.../all_aria2.txt](https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/all_aria2.txt)**_  
- _**[https://trackerslist.../http_aria2.txt](https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/http_aria2.txt)**_  

</details>

After copying the contents of the Aria2 Format Tracker file, paste it into the `bt-tracker=` tail in the `aria2.conf` configuration file. Example:
``` ini
bt-tracker=http://aaa.aa:80/announce,udp://bbb.bb:80/announce
```
> **Note:** Please delete the old Tracker content before pasting to avoid formatting errors!

****

#### BitComet:  

> <small>_**http://www.bitcomet.com**_</small>

<img src="https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/img/en-10.png" width="50%">

****

#### qBittorrent Enhanced Edition:

> <small>_**https://github.com/c0re100/qBittorrent-Enhanced-Edition**_</small>  
> <small>Based qBittorrent, added many useful features, such as **Subscribing to Tracker URL** , you can easily use with this project.</small>  

After saving the settings, be sure to **restart qBittorrent Enhanced Edition.**

<img src="https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/img/en-11.png" width="50%">

****

#### qBittorrent:

> <small>_**https://www.qbittorrent.org**_</small>

<img src="https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/img/en-12.png" width="50%">

****

#### Motrix:

> <small>_**https://motrix.app**_</small>

<img src="https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/img/en-13.png" width="50%">

****

#### File Centipede:

> <small>_**http://www.filecxx.com**_</small>

<img src="https://cdn.staticaly.com/gh/XIU2/TrackersListCollection/master/img/en-14.png" width="50%">

****

### Tracker Source

This project brings together the following list of public trackers:
* [https://github.com/ngosang/trackerslist](https://github.com/ngosang/trackerslist)
* [https://newtrackon.com/list](https://newtrackon.com/list)
* [http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt](http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt)
* [https://tinytorrent.net/best-torrent-tracker-list-updated/](https://tinytorrent.net/best-torrent-tracker-list-updated/)
* [http://www.torrenttrackerlist.com/torrent-tracker-list](http://www.torrenttrackerlist.com/torrent-tracker-list)
* [https://github.com/DeSireFire/animeTrackerList](https://github.com/DeSireFire/animeTrackerList)

Thanks for these projects!

****

### License
The GPL-3.0 License.  
