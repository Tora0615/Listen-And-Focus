# Listen-And-Focus

An app can listen music together whih friends, also can timing how long you focus on your job and compare with your partners.


### Function Description

* add music via youtube link
* only room owner can control play or pause.
* everyone can add song to playlist.
* can vote to cut/delete song.
  * maybe conbine is better.
* can cut in line to add song. (插播) (英文不確定)
* every can creat or jon room.
* every room can have many playlist.
  * playlist can be storage or just delete after listend.
  * maybe room id == user id is a good choice.
    * database is easy to design.
* Use flutter to design
  * hope can run at android, ios, macOS, windows, linux


### Database easy design

room id (user id)
- playlist
  - song a
  - song b
  - ...
- now_playing


### Some difficult part

* how to make everyone listen at the same play time, even when they join in different time. (播放進度相同)
* how to know someone is work hard or not.
