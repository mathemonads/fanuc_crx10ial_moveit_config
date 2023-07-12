# fanuc_crx10ial_moveit_config
MoveIt! configuration package for the Fanuc CRX-10iA/L

Demonstrates path planning in RViz is reflected in Gazebo.
TODO: Tune PID gains and constraints

## Requirements
Run Ubuntu 20 and ROS Noetic Ninjemys.

1. Install MoveIt.
`sudo apt-get install ros-noetic-industrial-core ros-noetic-moveit ros-noetic-tf2-tools`

2. Build fanuc-crx10ia-support.
`git clone https://github.com/ros-industrial/fanuc_experimental && cd ~/catkin_ws/ && catkin build`
...

## Launch
`roslaunch fanuc_crx10ial_moveit_config demo_gazebo.launch urdf_path:='$(find fanuc_crx10ial_moveit_config)/gazebo.urdf' --screen`
