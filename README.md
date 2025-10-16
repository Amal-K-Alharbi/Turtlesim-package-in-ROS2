# Run turtlesim package in ROS2

after installing Ubuntu MATE on VirtualBox than install ROS humble after that we start installing turtlesim

for using the turtlesim package we start with 
```
sudo apt install ros-humble-turtlesim
source /opt/ros/humble/setup.bash
ros2 pkg executables turtlesim
```
than using 
```
ros2 run turtlesim turtlesim_node
```
to open the turtlesim window
!()[]
!()[]
!()[]
and for controlling, we open another terminal and write
```
source /opt/ros/humble/setup.bash
ros2 run turtlesim turtle_teleop_key
```
