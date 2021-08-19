# Proto_arm
Proto is a simple DIY robotic arm made for learning robotic and ROS.

There are two types of URDF files, first one is "_description" files that are exported from Fusion 360 using Fusion2URDF plugin 	(https://github.com/syuntoku14/fusion2urdf). The second type of URDF files are "_moveit_config" files that have been processed by MoveIt setup assistant in order to control and simulate the robot arm. The "_moveit_config" files have "proto.launch" file in the "launch" folder, that launches both RViz and "serial_node.py" (https://github.com/ros-drivers/rosserial) that is located in folder "nodes".

Models inlcuding .stl, .step, and fimplified files will be uploaded at a later time.
