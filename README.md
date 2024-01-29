# ROS2 Transport robot_Innok Project

This project is a mobile robot application developed using ROS2. It features a two-wheeled car model created in Rhino and simulated in RVIZ. The robot is capable of performing translation and rotation movements. The primary goal of the project is to achieve optimized path motion for the car in complex environments, enhancing operational efficiency through manual control, autonomous driving, and optionally, advanced obstacle avoidance. 
![image](https://github.com/Guo-baiyi/Transport_robot/assets/120784487/677c29e8-766b-44a3-9102-743e71c7293c)


## Table of Contents
- [Overview](#overview)
- [Build Instructions](#build-instructions)
- [Dependencies](#dependencies)
- [Usage](#usage)
  - [Manual Control](#1-implement-manual-control)
  - [Autonomous Control](#2-implement-automatic-control)


## Overview

The mobile robot in this project is modeled using Rhino and simulated in RVIZ. It is equipped with functions for manual control, autonomous driving, and optional advanced obstacle avoidance. The focus is on achieving optimized path motion in complex environments, allowing the selection of multiple points to optimize into rounded corners or B-spline curves.

## Build Instructions

### Prerequisites
- Install ROS2: [ROS2 Installation Guide](https://docs.ros.org/en/galactic/Installation.html)
- Install Rviz2

### Build Steps
1. Clone this repository.
2. Navigate to the project directory.
3. Build the project using the following commands:

```bash
$ colcon build
$ source install/setup.bash 
```


## Usage

### 1. Implement Manual Control

To manually control the car's movement using a virtual joystick:

```bash
$ ros2 launch telema_pkg01 manual_path.py
$ rviz2
```
Drag the right joystick to control the car forward, backward and steering. 

<img width="1085" alt="1" src="https://github.com/Guo-baiyi/Transport_robot/assets/120784487/280d0966-a3f8-488a-b327-2a7d254fcf70"> 


### 2. Implement Automatic Control

To enable automatic control for the car:

```bash
$ ros2 launch automation auto_launch.py
$ rviz2
```
<img width="1089" alt="2" src="https://github.com/Guo-baiyi/Transport_robot/assets/120784487/fbbb74ea-acbb-4e54-88d8-b715b684f8ae">









