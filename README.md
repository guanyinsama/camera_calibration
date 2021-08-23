## 摄像头校正的包

[camera_calibration](http://wiki.ros.org/camera_calibration/)

## 查看摄像头信息

sudo apt-get install v4l-utils

查看电脑连接的摄像头：

v4l2-ctl --list-devices

查看摄像头详细信息：

v4l2-ctl -d  /dev/video0 --all