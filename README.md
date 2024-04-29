# InfraredSensorModule

## Introduction
This repository contains documentation for my Semester III Project to satisfy the coursework of "Mini Project". This repository generally does not contain code but resource files of the Infrared Sensor Module.

## Project Overview
[Circuit Diagram.pdf](https://github.com/Ashutoshss/InfraredSensorModule/files/15153404/Circuit.Diagram.pdf)

## Required Components
- IC LM358
- IR Receiver
- IR Transmitter
- Resistor ()
- 5v Power Supply
- Indicator

## Circuit Diagram
  ![image](https://github.com/Ashutoshss/InfraredSensorModule/assets/103228643/764b7738-4fbd-43d9-8f2a-6d3121ac628b)

## Process Of Creation of PCB for the Module
1. **:** 
2. **ROS2 Humble Installation:** Refer to the ROS2 Humble documentation [here](https://docs.ros.org/en/humble/index.html) for installation instructions.
3. **Computer Vision:**
  ```bash
  pip3 install opencv-contrib-python==4.7.0.72
  pip3 install numpy==1.21.5
  ```
6. **Gazebo:** Gazebo Reference [here](https://classic.gazebosim.org/tutorials).
7. **Rviz:** Rviz is included with ROS2, so ensure it's installed along with ROS2.[here](https://classic.gazebosim.org/tutorials?tut=drcsim_visualization&cat=drcsim)
## Additional Packages
1. **MoveIt:**
   - To install MoveIt containing all packages ready for deployment, run:
     ```bash
     sudo apt install ros-humble-moveit
     ```

2. **Joint State Broadcaster:**
   - This package publishes joint states to a topic, enabling other dependent nodes to know about the state of each joint. To install, run:
     ```bash
     sudo apt install ros-humble-joint-state-publisher
     ```




## Video Documentation
[![Video Submission for task2a](https://img.youtube.com/vi/YOUR_VIDEO_ID_HERE/0.jpg)](https://youtu.be/mkCT9SrxkP4?si=ET5bD1K9u_ZSkSv1)

[![Video Submission for task2b](https://img.youtube.com/vi/YOUR_VIDEO_ID_HERE/0.jpg)](https://youtu.be/AUCwfSHWFOo?si=GIza9xTLzzItvdli)

[![Video Submission for task3b](https://img.youtube.com/vi/YOUR_VIDEO_ID_HERE/0.jpg)](https://youtu.be/-_gF3-TqrlM?si=yQI4Bg9eGw3DysPP)



## Repository Owner
- Ashutosh Shrikant Singh
