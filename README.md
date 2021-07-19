# Listen-And-Focus

An app can listen music together whih friends, also can timing how long you focus on your job and compare with your partners.


### Function Description

* add music via youtube link
* only room owner can control play or pause.
* everyone can add song to playlist.
* can vote to cut/delete song/playlist.
  * maybe conbine is better.
* can cut in line to add song. (插播) (英文不確定)
* every can creat or join room.
* every room can have many playlist.
  * playlist can be storage or just delete after listend.
  * maybe room id == user id is a good choice.
    * database is easy to design.
* form join the room, focus time stop to add.
* can compare focus time with friends.
* Use flutter to design
  * hope can run at android, ios, macOS, windows, linux

### MVP (minimum viable product, 最小可行性產品) need functions





### MVP Database design

- room id / user id (String)
  - playlist list
    - playlist a (String List)
      - song a
      - song b
      - ...
    - playlist b (String List)
      - song a
      - song b
      - ...
  - nowPlayingIndex (int)
  - nowPlayingTime (Time)
  - isPlaying (Bool)



### Some difficult part

* how to make everyone listen at the same play time, even when they join in different time. (播放進度相同)
* how to know someone is work hard or not.
