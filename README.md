# pick_place
This is a folder demo of pick and place using moveit task constructor. To run this code make sure to have build moveit and moveit task constructor packages. Download the package and run  ros2 launch moveit2_tutorials mtc_demo.launch.py and ros2 launch pick_place pick_place.launch.py. 
The detailed instructions can be found in moveit turtorails for pick and place.

# Pick and Place Robot System

## Overview
This is a  pick and place project using moveit task constructor and ros2(humble). The whole code is written is c++. 


## Getting Started

To get started install the 

### Prerequisites

-ROS2 humble (Robot Operating System) [Link to ROS Installation Guide](https://docs.ros.org/en/humble/Installation.html)
- MoveIt! [Link to MoveIt! Installation Guide](https://moveit.picknik.ai/humble/doc/tutorials/getting_started/getting_started.html)

### Installation
Create a ros2 package, ensure to have sourced the moveit build, follow this steps to install pick and place.

```bash
git clone https://github.com/Hemanth95/pick_place.git
cd src/pick_place
```
### Running the program
```bash
ros2 launch moveit2_tutorials mtc_demo.launch.py
ros2 launch pick_place pick_place.launch.py
```
### Acknowledgements

We would like to express our gratitude to the following:

    Moveit for moveit task contributor.


