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
Go to the folder
```shell
cd ~/catkin_ws/src/urdf/launch
```

To visualize in rviz, enter this command :
```shell
roslaunch urdf display.launch
```
The cyberdog_3d_model_fusion 360 folder contains a robot model made in Fusion 360

Visualization in rviz

![Screenshot from 2023-08-26 16-04-38](https://github.com/RubSevian/Xiaomi_Cyberdog_3D_Model/assets/109359327/38be2e76-bcbf-439f-b771-1822ad968be5)

![Screenshot from 2023-08-26 16-05-50](https://github.com/RubSevian/Xiaomi_Cyberdog_3D_Model/assets/109359327/3e691d3e-ee17-4eaf-82ac-10f92900b059)
