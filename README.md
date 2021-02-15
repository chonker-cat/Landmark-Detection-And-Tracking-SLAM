# Landmark Detection And Tracking (SLAM)
This project was part of my computer vision course of [Udacity](https://www.udacity.com/course/computer-vision-nanodegree--nd891). 
In this project, a robot localizes a 2D grid world. The basis for simultaneous localization and mapping ([SLAM](https://en.wikipedia.org/wiki/Simultaneous_localization_and_mapping)) is to gather information from the robot's sensors and motions over time, 
and then use information about measurements and motion to re-construct a map of the world.

The Robot are referring poses as Px, Py and landmark positions as Lx, Ly, and add all to a constraint matrices.
<img src='images/constraints2D.png' width=50% height=50% />

The equation below is used to calculate robot poses and locations of landmarks.   
<img src='images/solution.png' width=30% height=30% />


## Important files
- **1. Robot Moving and Sensing.ipynb** : Introduction to the robot class and its map.
- **2. Omega and Xi, Constraints.ipynb** : Introduction to Graph SLAM.
- **3. Landmark Detection and Tracking.ipynb** : The robot explores its 2D world using Graph SLAM.
- **robot_class.py** : The robot class with move and sense functions.
    
    
## Installation and usage
Clone the repository
```sh
$ cd <your workspace folder>
$ https://github.com/embmike/Landmark-Detection-And-Tracking-SLAM.git
```

You can use the code for example on your computer with [Anaconda](https://www.anaconda.com/) or via cloud computing with [Google Colaboratory](https://colab.research.google.com/). 
    
    
## Licence
This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

