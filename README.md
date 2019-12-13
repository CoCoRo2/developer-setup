# Development Environment for Baxter's Mobility Base

<details>
  <summary>
    <strong>Table of Contents</strong>
    <small><i>(🔎 Click to expand)</i></small>
  </summary>

* [Features](#features)
* [Screenshot](#screenshot)
* [Pre-requisites](#pre-requisites)

</details>

## Features

- Fast development environment setup using containers and compose files
- Complete `ROS Kinetic` environment for real or simulated environments with
  - lifelong `SLAM`<sup>[1](#1)</sup> for large areas (like warehouses, retail,
  etc.)
  - navigation
  - exploration
  - pose accuracy
  - Gazebo 8.0 simulator
- Known Pose API for storing and retrieving (accurate<sup>[2](#2)</sup>) poses
- Web Application and UI for interacting with the base
- Jupyter notebooks for rapid prototyping integrated with
  - Python2.7 and Python3.8
  - ROS Kinetic
  - OpenCV 4.1.0
  - Octave 4.4.1
  - RealSense cameras
- Compose files defining different configurations of services for launching different
  - algorithms for SLAM, planners, environments (in simulator), etc.
  - scenarios for navigation, exploration, etc.
  - network setups (SDN, Docker Swarm)
- Templates for creating new ROS nodes in C++11 and Python2.7


<a name="1">1</a>: SLAM: Simultaneous Localization and Mapping

<a name="2">2</a>: Accurate poses define 6D poses with high precision.
They can - in a later step - be used for final pose adjustment with
sub-centimeter positional and sub-degree orientational accuracy

## Screenshot

## Pre-requisites


[^1]: SLAM: 
