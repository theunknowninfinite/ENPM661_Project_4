
# ENPM661 - Project Four
## Authors

- [Suriya Suresh](https://www.github.com/theunknowninfinite)
- [Aashrita Chemakura](https://github.com/aashrita-chemakura)

## 1. Project Goals

1. Implementation of MoveIt Motion Planning on the
Panda Robotic Arm.


## 2. Packages Used 
The code uses the standard ROS C libraries.
This was done on Ubuntu 20.04 with ROS Noetic.


## 3. Setting up the script

1. Clone the github repos Panda moveit configs[https://github.com/ros-planning/panda_moveit_config.git] (Noetic Branch) and moveit_tutorials[https://github.com/ros-planning/moveit_tutorials.git] (Master Branch).

2. Clone the above github repo and place it under docs/pick_place of moveit_tutorials, replacing the existing files under it. 
```` 
$ git clone link-of-repo
````
3. Do catkin_make to compile the package with recent changes included.
```` 
$ catkin_make
````
4. Launch Rviz by running 
```` 
$ roslaunch panda_moveit_config demo.launch
````
5. Run the pick_place package to visualize the planned path.
```` 
$ rosrun moveit_tutorials pick_place_tutorial
````
6. The output can be seen in the Rviz window. 
## 4. Output
The output can be found under Videos. 
## Credits 
The authors of the moveit package for their excellent documentation and tutorials.
## Support

For support, open a issue on Github.










