# Xiaomi_Cyberdog_3D_Model
3D model of Xiaomi Cyberdog robot and urdf model.

## Installation
Ubuntu version 20.04 
ROS version Noetic

Note, when opening the terminal (in the home directory), write this command:
```shell
source /opt/ros/YOUR_ROS1_DISTRO/setup.bash
```
Create a folder catkin_ws/src 
```shell
mkdir -p catkin_ws/src
cd catkin_ws/src
```
Git clone the repo:
```shell
https://github.com/RubSevian/Xiaomi_Cyberdog_3D_Model.git
```
Put our urdf folder in src folder

After transferring the urdf folder to the src folder, enter:
```shell
cd ~/catkin_ws
```

And assemble the package :
```shell
catkin_make
```
To visualize in rviz, enter this command :
```shell
roslaunch urdf display.launch
```

Visualization in rviz

![Screenshot from 2023-07-24 20-29-39](https://github.com/RubSevian/Xiaomi_Cyberdog_3D_Model/assets/109359327/1325be60-d451-4380-9493-15c17f34e0e2)

![Screenshot from 2023-07-24 20-27-45](https://github.com/RubSevian/Xiaomi_Cyberdog_3D_Model/assets/109359327/3154c2cf-274a-4cbe-9b7b-638ecd179921)
