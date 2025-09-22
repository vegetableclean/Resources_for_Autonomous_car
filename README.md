# QCar-Related Resources

This repository contains resources related to **QCar** development:  
👉 https://www.quanser.com/products/qcar-2/  

It includes example files for cameras and LiDARs to help you get started with sensor integration in ROS/ROS2 environments.

## Included Resources

- `realsense-ros-ros2-master`  
  Example files and configurations for integrating **Intel RealSense** cameras in ROS and ROS2.

- `rplidar_ros-master`  
  Example files and configurations for integrating **RPLIDAR** sensors in ROS.

- `eis-fe8kv9-master`  
  Example files for **YOLOv9 fisheye integration** with **CSI cameras**.  
  Useful for experiments with end-to-end object detection on embedded systems.

## Prerequisites

- ROS (e.g., ROS Noetic) or ROS2 (e.g., ROS2 Foxy) installed and configured.
- Intel RealSense SDK for `realsense-ros-ros2-master`.
- RPLIDAR drivers for `rplidar_ros-master`.
- OpenCV / PyTorch for `eis-fe8kv9-master` if using YOLOv9 fisheye detection.

## Installation

Clone the repository into your ROS workspace:

##Other application
Lidar detection https://github.com/sreesms/lidar_obstacle_detection_ros

```bash
cd ~/your_ros_workspace/src
git clone <your-repo-url>

