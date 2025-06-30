# blaze101_description

## Basler Blaze-101 3D Camera URDF Description for ROS

This repository contains the URDF and 3D mesh files necessary to integrate the Basler Blaze-101 Time-of-Flight (ToF) camera into a ROS-based robot model, specifically designed for Clearpath Husky A200 but can be adapted to other robots.

---

## Overview

- **Robot model integration**: Allows visualization of the Blaze-101 camera directly in RViz, linked properly to the robot's TF tree.
- **Custom 3D mesh**: Includes a detailed `.dae` model of the Blaze-101 for accurate rendering.
- **URDF/Xacro macros**: Easy to include and position on custom robot URDFs.

## 📁 Structure

blaze101_description/
├── CMakeLists.txt
├── package.xml
├── meshes/
│ └── baslerBlaze101.dae
├── urdf/
│ └── blaze101.urdf.xacro

## ⚙️ Usage

1. Clone this repository into your workspace:

```bash
cd ~/catkin_ws/src
git clone https://github.com/your_username/blaze101_description.git
cd ~/catkin_ws
catkin_make
