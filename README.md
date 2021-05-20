# My_2wheel_robot_with_camera_laidar
#########my_robot

Install ROS-NOETIC from http://wiki.ros.org/noetic/Installation/Ubuntu 

$cd ~/catkin_ws/src

#add this package in src directory
clone this repo in your ~/catkin_ws/src directory

$cd ~/caktin_ws

$catkin_make

$ source devel/setup.bash
$ roslaunch my_robot world.launch

$ rostopic pub /cmd_vel geometry_msgs/Twist  "linear:
  x: 0.3
  y: 0.0
  z: 0.0
angular:
  x: 0.0
  y: 0.0
  z: 0.2" 
