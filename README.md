# Line Follower TurtleBot
SUSTECH EE346 zhanchenzhi#12012505 zhangyuxuan#12012508

# Usage

## 1.Clone the source code
cd ~/catkin_ws/src/line_follower_turtlebot

git clone git@github.com:MarkzcZ/ROS_ArUco.git

## 2.Catkin make the file
cd..

catkin_make

## 3.Run in the RBC
ssh pi@yourpi_ip

roslaunch turtlebot3_bringup turtlebot3_robot.launch

## 4.Run in the PC
roscore

roslaunch line_follower_turtlebot lf.launch

roslaunch line_follower_turtlebot aruco_marker_finder.launch

