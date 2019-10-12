# XIU2/TrackersListCollection

[![GitHub license](https://img.shields.io/github/license/XIU2/TrackersListCollection.svg?style=flat-square)](https://github.com/XIU2/TrackersListCollection/blob/master/LICENSE)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg?style=flat-square)](https://996.icu)

Updated daily! A list of popular public BitTorrent trackers.  

The project only makes a list of popular public trackers into collections.  

[中文说明请看这里](https://github.com/XIU2/TrackersListCollection/blob/master/README-ZH.md)

****

### Updated: 2019-10-13

*These lists are automatically updated every day:*

> Better public tracker list is relatively more stable, concise.  
> Complete public tracker list is more in number and theoretically better. but there may be some invalid trackers.  
> **The number of Tracker does not affect the operation of the BT software, so I recommend using the full list to maximize the download speed !**

* **Better public tracker list:** (72 trackers)  
[https://trackerslist.com/trackers_best.txt](https://trackerslist.com/trackers_best.txt)
* **Complete public tracker list:** (439 trackers)  
[https://trackerslist.com/trackers_all.txt](https://trackerslist.com/trackers_all.txt)

****

#### Aria2 Tracker

To make it easier for people using Aria2 to add Tracker, I made a separate copy in the Aria2 configuration format. The update is consistent.

* **Better public tracker list:**  
[https://trackerslist.com/trackers_best_aria2.txt](https://trackerslist.com/trackers_best_aria2.txt)
* **Complete public tracker list:**  
[https://trackerslist.com/trackers_all_aria2.txt](https://trackerslist.com/trackers_all_aria2.txt)

[Aria2 Instructions](https://github.com/XIU2/TrackersListCollection#Aria2)

****

### Tracker Source

This project brings together the following list of public trackers:
* [https://github.com/ngosang/trackerslist](https://github.com/ngosang/trackerslist)
* [https://newtrackon.com/list](https://newtrackon.com/list)
* [https://torrents.io/tracker-list/](https://torrents.io/tracker-list/)
* [http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt](http://github.itzmx.com/1265578519/OpenTracker/master/tracker.txt)
* [https://tinytorrent.net/best-torrent-tracker-list-updated/](https://tinytorrent.net/best-torrent-tracker-list-updated/)
* [https://torrenttrackerss.com/torrent-tracker-list/](https://torrenttrackerss.com/torrent-tracker-list/)
* [http://www.torrenttrackerlist.com/torrent-tracker-list](http://www.torrenttrackerlist.com/torrent-tracker-list)

Thanks for these projects!

****

### How to use ?

#### Aria2

After copying Aria2 Tracker, paste it into the `bt-tracker=` tail in the `aria2.conf` configuration file. Example:
``` ini
bt-tracker=http://xxx.xx:80/announce,udp://yyy.yy:80/announce
```
> **Note:** Please delete the old Tracker content before pasting to avoid formatting errors!

****

#### BitComet

![BitComet Tracker](https://github.com/XIU2/TrackersListCollection/raw/master/img/en-02.png)

### Contribute

* Do you know more public trackers list? (E.g: ngosang/trackerslist) => [Open a new issue](https://github.com/XIU2/TrackersListCollection/issues/new)

****

### License
The GPL-3.0 License.  
The Anti-996 License.
