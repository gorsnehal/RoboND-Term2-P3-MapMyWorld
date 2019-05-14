# RoboND-Term2-P3-MapMyWorld
Udacity Robotics ND - Term 2 - Project 3 : SLAM and Mapping

Build ROS package to create both a 2D and 3D map of the supplied environment. Then build your own environment and use your ROS package to generate a 2D and 3D map of that environment. 

## Installation, Build & Running Scripts ##

* Following package installation might be required (Assumed that Linux 16.04 and ROS Kinetic installation is already there)
```
$ sudo apt-get install ros-kinetic-rtabmap
```

* Download the repository folder 'mapworld_sg' to catkin workspace folder
Use following command to clone entire repository, and then copy 'mapworld_sg' folder to your catkin_ws/src folder.
```
$ git clone https://github.com/gorsnehal/RoboND-Term2-P3-MapMyWorld.git
```
* Compile & Build the mapworld_sg package
```
catkin_make
source devel/setup.bash
```
* After the above steps, you should be able to run the commands below in separate terminals for Udacity provided world
```
roslaunch mapworld_sg slam_world.launch
roslaunch mapworld_sg teleop.launch
roslaunch mapworld_sg mapping.launch
roslaunch mapworld_sg rviz.launch
```
* For the World I have created, you should be able to run the commands below in separate terminals (Optional)
```
roslaunch mapworld_sg sg_slam_world.launch
roslaunch mapworld_sg teleop.launch
roslaunch mapworld_sg sg_mapping.launch
roslaunch mapworld_sg rviz.launch
```


## Refer project Report 'Map_My_World___ROS_RTABMap.pdf' for technical details ##