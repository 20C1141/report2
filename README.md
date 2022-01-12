# report2
ロボットシステム学　課題2

# 概要
ロボットシステム学の第10回講義動画を見てパッケージ、ノード、パブリッシャ、サブスクライバを作成する。

ラズパイ上でROSを用いて、定期的にデータを投げトピックとして得たデータを表示する。

# 実行動画
https://youtu.be/JRWDjip2B3s

# 動作環境
Raspberry Pi 3 (ModelB)

ubuntu20.04 LTS

ROS

# インストール方法
$ cd catkin_ws/src/

$ git clone https://github.com/20C1141/report2.git

$ cd .. 

$ catkin_make

$ source ~/.bashrc

# 実行方法
端末1でroscoreを立ち上げる。

$ roscore

端末2でcount.pyを実行する。

$ rosrun mypkg count.py

端末3でtwice.pyを実行する。

$ rosrun mypkg twice.py

端末4で

$ rostopic echo /twice


# ライセンス
BSD 3-Clause License

# 著者
Soya Watabe +　Ryuichi Ueda
