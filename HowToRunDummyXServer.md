# HowToRunDummyXServer
# reference
[techoverflow](https://techoverflow.net/2019/02/23/how-to-run-x-server-using-xserver-xorg-video-dummy-driver-on-ubuntu/)

# RUN 
```
sudo X -config ./dummy_x.conf.nvidia-xconfig-original
DISPLAY:=<number> ros2 launch ~~
```
