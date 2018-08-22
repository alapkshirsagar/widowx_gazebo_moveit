## Quick Start:

mkdir -p ~/catkin_ws_widowx/src

cd ~/catkin_ws_widowx/src

git clone https://github.com/alapkshirsagar/widowx_gazebo_moveit.git

cd ~/catkin_ws_widowx

catkin_make

source devel/setup.bash

roslaunch widowx_arm_bringup arm_moveit.launch sim:=false sr300:=false

## Object manipluation:

roslaunch widowx_arm_bringup arm_moveit.launch sim:=false sr300:=true

roslaunch widowx_block_manipulation block_sorting_demo.launch
