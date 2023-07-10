# fanuc_crx10ial_moveit_config
MoveIt! configuration package for the Fanuc CRX-10iA/L

Demonstrates path planning in RViz is reflected in Gazebo.
TODO: Tune PID gains and constraints

## Launch
`roslaunch fanuc_crx10ial_moveit_config demo_gazebo.launch urdf_path:='$(find fanuc_crx10ial_moveit_config)/gazebo.urdf' --screen`
