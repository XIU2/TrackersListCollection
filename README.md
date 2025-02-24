# XIU2/TrackersListCollection

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square&color=4285dd&logo=github)](https://github.com/XIU2/TrackersListCollection/)
[![GitHub Star](https://img.shields.io/github/stars/XIU2/TrackersListCollection.svg?style=flat-square&label=Star&color=4285dd&logo=github)](https://github.com/XIU2/TrackersListCollection/)
[![GitHub Fork](https://img.shields.io/github/forks/XIU2/TrackersListCollection.svg?style=flat-square&label=Fork&color=4285dd&logo=github)](https://github.com/XIU2/TrackersListCollection/)
[![TrackersList.com](https://img.shields.io/static/v1?label=%20&message=TrackersList.com&style=flat-square&labelColor=4B93F1&color=4285dd&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAYUlEQVR42mP0nvzxPwMFgBHdgOYAbji7dsNX0g1IseeEs+cc/E68AVty+Ehyus+UT4PNAGxhEKDLiqGBYCDCYuHh+3/DzYANl38zyAsywfmwRDYIDUAGyGmD6DCgqgHEAADqpnHxT0ZWTwAAAABJRU5ErkJggg==)](https://trackerslist.com)

Updated daily! A list of popular BitTorrent Trackers. **If you feel good, please [⭐](https://github.com/XIU2/TrackersListCollection/stargazers)!**  

I've put together a kick-ass list of top-notch trackers by scouring the web and handpicking only the best ones. It's good enough for my own use, so I thought I'd share it with y'all~  

> 「[简体中文](https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md)」(位于 [trackerslist.com](https://trackerslist.com/#/zh) 的访客，可通过右上角切换语言 ↗)  

**** 

### What is Tracker?

Tracker plays a necessary role in BT download, it can effectively improve BT download speed.  

> Record user information that downloads the same resource to **help you connect with other users**.  

_The figure below shows the BT download speed after using Tracker. (best.txt)_  

![BitComet](https://bitbucket.org/xiu2/trackerslistcollection/raw/master/img/en-01.png)
![qBittorrentEE](https://bitbucket.org/xiu2/trackerslistcollection/raw/master/img/en-02.png)

_You can judge whether there is a problem with the BT configuration and network by observing the download speed of [**ubuntu.torrent**](https://ubuntu.com/download/alternative-downloads#bittorrent). There are many users of this popular resource, and the download speed should be very fast under normal circumstances._

****

### Updated: 2025-02-25

- **BEST Tracker list:** (64 trackers)  
 _**https://cf.trackerslist.com/best.txt**_  
- **ALL Tracker list:** (148 trackers)  
 _**https://cf.trackerslist.com/all.txt**_  
- **HTTP(S) Tracker list:** (80 trackers)  
 _**https://cf.trackerslist.com/http.txt**_  
- **No HTTP Tracker list:** (89 trackers)  
 _**https://cf.trackerslist.com/nohttp.txt**_  

<details>
<summary><strong><code>[Click to expand] - View alternate address</code></strong></summary>

****

\# **Here is an example of a selection of `best.txt` (modify the file name as needed):**  

- _**https://bitbucket.org/xiu2/trackerslistcollection/raw/master/best.txt**_  
- _**https://cdn.jsdelivr.net/gh/XIU2/TrackersListCollection/best.txt**_  
- _**https://fastly.jsdelivr.net/gh/XIU2/TrackersListCollection/best.txt**_  
- _**https://gcore.jsdelivr.net/gh/XIU2/TrackersListCollection/best.txt**_  
- _**https://cdn.statically.io/gh/XIU2/TrackersListCollection/best.txt**_  
- _**https://raw.githubusercontent.com/XIU2/TrackersListCollection/master/best.txt**_  

</details>

****

### How to use?

#### Aria2:

<details>
<summary><strong><code>[Click to expand] - View the tracker list in Aria2 format</code> </strong></summary>

- ***https://cf.trackerslist.com/best_aria2.txt***  
- ***https://cf.trackerslist.com/all_aria2.txt***  
- ***https://cf.trackerslist.com/http_aria2.txt***  
- ***https://cf.trackerslist.com/nohttp_aria2.txt***  

</details>

After copying the contents of the Aria2 Format Tracker file, paste it into the `bt-tracker=` tail in the `aria2.conf` configuration file. Example:
``` ini
bt-tracker=http://aaa.aa:80/announce,udp://bbb.bb:80/announce
```
> **Note:** Please delete the old Tracker content before pasting to avoid formatting errors!

****

#### BitComet:  

> <small>_**http://www.bitcomet.com**_</small>

<img src="https://bitbucket.org/xiu2/trackerslistcollection/raw/master/img/en-10.png" width="50%">

****

#### qBittorrent Enhanced Edition:

> <small>_**https://github.com/c0re100/qBittorrent-Enhanced-Edition**_</small>  
> <small>Based on qBittorrent, added many useful features, such as **Subscribing to Tracker URL**, which you can easily use with this project.</small>  

After saving the settings, be sure to **restart qBittorrent Enhanced Edition.**

<img src="https://bitbucket.org/xiu2/trackerslistcollection/raw/master/img/en-11.png" width="50%">

****

#### qBittorrent:

> <small>_**https://www.qbittorrent.org**_</small>

<img src="https://bitbucket.org/xiu2/trackerslistcollection/raw/master/img/en-12.png" width="50%">

****

#### Motrix:

> <small>_**https://motrix.app**_</small>

<img src="https://bitbucket.org/xiu2/trackerslistcollection/raw/master/img/en-13.png" width="50%">

****

> In addition, considering that the project is just a small project with simple functions, I don't want to involve too much energy, **so I closed Issues and no longer accept submission Tracker addresses.**  

> If you find an obvious error, or want to delete a Tracker, you can submit a **Pull request** to alert me.

****

### Tracker Source

This project brings together the following list of public trackers:
* https://github.com/ngosang/trackerslist
* https://newtrackon.com/list
* https://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt
* https://tinytorrent.net/best-torrent-tracker-list-updated/
* https://www.torrenttrackerlist.com/torrent-tracker-list
* https://github.com/DeSireFire/animeTrackerList

Thanks for these projects!

****

### License
The GPL-3.0 License.  
