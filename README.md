# Listen-And-Focus

An app can listen music together whih friends, also can timing how long you focus on your job and compare with your partners.


### Function Description

* Music adding part
  * add music via youtube link
  * everyone can add song to playlist.
  * can cut in line to add song. (插播) (英文不確定)

* Music Playing part
  * only room owner can control play or pause.
  * can vote to cut/delete song/playlist.
    * everyone can raise this vote.
    * maybe conbine cut and delete is better.

* Music room part
  * every can creat or join room.
  * every room can have many playlist.
    * playlist can be storage or just delete after listend.
      * maybe need to choose what playlist mode before creat a room.
    * for storage playlist maybe room id == user id is a good choice.
      * database is easy to design.

* Foucs funcion part
  * timing erery user's foucus time.
  * user can control it's status (focus/rest)
  * sort the foucus time
    * can compare focus time with friends.

* Tool to use
  * Use flutter to design
    * hope can run at android, ios, macOS, windows, linux

### MVP (minimum viable product, 最小可行性產品) need functions

* Focus timer
  * control button : Keep Focus (繼續專注) and Take a rest (休息一下)



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
  - Focus ranking (List)
    - user a : time
    - user b : time



### Some difficult part

* how to make everyone listen at the same play time, even when they join in the different time. (播放進度相同)
* how to know someone is work hard or not.
  * 自由心證



### Some good idea?
* how long don't login