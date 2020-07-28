# GoPiGo3 ROS Software

## Commands executed on pi

* `roslaunch gpg_bran gopigo3_ydlidar.launch` - start  gopigo3 node (for odom and cmd_vel) and the lidar node (for scan)
* `roslaunch gpg_bran camerav2_1280x960.launch` - turn on camera

## Commands executed on remote computer

* `rosrun gpg_bran imv_view.py` - view image from the camera
* `rosrun gpg_bran key_teleop.py` - teleoperation with cursor keys
* `roslaunch gpg_bran gopigo3_slam.launch` - begin slam to build a map
* `roslaunch gpg_bran amcl.launch map_file:=/home/ubuntu/catkin_ws/test_map.yaml` - launch localization based on specified ma

## General ROS commands (not from us)

* `rosrun map_server map_saver -f ~/catkin_ws/test_map` - Save map to specified file

## Other files


