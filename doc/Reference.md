# Dashboard README

Dashboard design for robot control system

**https://0e1ka10.github.io/UserInterface**



# Detail of CSS, JS

- Bootstrap(v4.5.2)
- Admin-LTE(v3.0.5)
- Chart.js(v2.9.3)
- jQuery(v3.5.1)
- Fontawesome(v5.14.0)
- Ionicons(v2.1.0)
- ros2djs
- nav2djs



# Running the dashboard

### ros2djs

Simply launch with the following command.
You will need to have[map_server](http://wiki.ros.org/map_server), [rail_maps](http://wiki.ros.org/rail_maps), and [rosbridge_server](http://wiki.ros.org/rosbridge_server) installed.

```sh
$ roscore
$ rosrun map_server map_server <your pc's directory>/img/map/test_map.pgm 0.05
$ roslaunch rosbridge_server rosbridge_websocket.launch
```



# About the directory

### ~/img

- __./icons__：htmlファイル上で表示する画像，その他について格納してあるディレクトリ
- __./map__：.ppm，.png形式でのロボットが走行を行う地図のイメージを格納したディレクトリ
- __./sample__：完成イメージ参考用，その他使用していないイメージ等の格納に使用

### ~/bks

htmlのバックアップ保存用ディレクトリ

### ~/doc

このREADME等のドキュメントファイル保存ディレクトリ

### ~/vid
キャプチャしたビデオの保存用ディレクトリ



# Links

### CSS, JS

- [Admin-LTE](https://adminlte.io/)
- [Bootstrap](https://getbootstrap.com/)
- [Chart.js](https://www.chartjs.org/)
- [jQuery](https://jquery.com/)
- [Fontawesome](https://fontawesome.com/)
- [Ionicons](https://ionicons.com/)
- [ros2djs in ROS](http://wiki.ros.org/ros2djs)
- [nav2djs in ROS](http://wiki.ros.org/nav2djs)

### 参考リンク集

- [Bootstrapのグリッドシステムの使い方を初心者に向けておさらいする](http://websae.net/twitter-bootstrap-grid-system-21060224/)
- [Introduction-AdminLTE 3](https://adminlte.io/docs/3.0/index.html)
- [cdnjs admin-lte](https://cdnjs.com/libraries/admin-lte)
- [Chart.jsでグラフを描画してみた-Qiita](https://qiita.com/Haruka-Ogawa/items/59facd24f2a8bdb6d369)

