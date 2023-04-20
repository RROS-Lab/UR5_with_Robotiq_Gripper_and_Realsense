# UR5_with_Robotiq_Gripper_and_Realsense
URDF of UR5 with Robotiq Gripper and Realsense Camera

Download dependencies and place in the package appropriately.


[Universal Robot Description](https://github.com/nLinkAS/fmauch_universal_robot)

<xacro:include filename="$(find ur_description)/urdf/inc/ur5_macro.xacro" />

Customize Realsense mount by placing STL file on the mesh
<xacro:include filename="$(find ur5_with_robotiq_gripper_des)/urdf/realsense_mount.xacro" />

[Robotiq Gripper](https://github.com/ros-industrial/robotiq)
<xacro:include filename="$(find robotiq_2f_85_gripper_visualization)/urdf/robotiq_arg2f_85_model_macro.xacro" />

[Universal Robot Description](https://github.com/nLinkAS/fmauch_universal_robot)
<xacro:include filename="$(find realsense2_description)/urdf/_d415.urdf.xacro" />
