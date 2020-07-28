# GoPiGo3 ROS Software

## Commands executed on pi

* `roslaunch gpg_bran gopigo3_ydlidar.launch` - start  gopigo3 node (for odom and cmd_vel) and the lidar node (for scan)
* `roslaunch gpg_bran camerav2_1280x960.launch` - turn on camera

## Commands executed on remote computer

* `rosrun gpg_bran imv_view.py` - view image from the camera
* `rosrun gpg_bran key_teleop.py` - teleoperation with cursor keys
* `roslaunch gpg_bran gopigo3_slam.launch` - begin slam to build a map

## General ROS commands (not from us)
## Other files


