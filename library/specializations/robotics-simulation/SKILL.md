---
name: specialization-robotics-simulation
description: "The Robotics and Simulation Engineering specialization encompasses the design, development, testing, and deployment of robotic systems and their digital twins. This specialization combines mechanical engineering, electronics, computer science, control theory, and advanced simulation techniques to…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: robotics-simulation
  process-count: 30
---

# specialization-robotics-simulation

## Overview

The Robotics and Simulation Engineering specialization encompasses the design, development, testing, and deployment of robotic systems and their digital twins. This specialization combines mechanical engineering, electronics, computer science, control theory, and advanced simulation techniques to create intelligent machines that can perceive, reason, and act in the physical world.

## Available Processes (30)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/robotics-simulation/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `autonomous-exploration` (`specializations/robotics-simulation/autonomous-exploration`) | Autonomous Exploration and Mapping - Implement frontier-based autonomous exploration for |
| `digital-twin-development` (`specializations/robotics-simulation/digital-twin-development`) | Digital Twin Development - Create accurate digital twin of physical robot for development and |
| `dynamic-obstacle-avoidance` (`specializations/robotics-simulation/dynamic-obstacle-avoidance`) | Dynamic Obstacle Avoidance - Implement real-time obstacle avoidance for mobile robots including |
| `field-testing-validation` (`specializations/robotics-simulation/field-testing-validation`) | Field Testing and Validation - Comprehensive field testing of robot systems in real-world |
| `gazebo-simulation-setup` (`specializations/robotics-simulation/gazebo-simulation-setup`) | Gazebo Simulation Environment Setup - Create high-fidelity simulation environment using Gazebo |
| `hil-testing` (`specializations/robotics-simulation/hil-testing`) | Hardware-in-the-Loop (HIL) Testing - Implement comprehensive HIL testing framework for |
| `human-robot-interaction` (`specializations/robotics-simulation/human-robot-interaction`) | Human-Robot Interaction (HRI) Interface - Develop intuitive and safe human-robot interaction |
| `imitation-learning` (`specializations/robotics-simulation/imitation-learning`) | Imitation Learning from Demonstrations - Train robot policy from human demonstrations using |
| `isaac-sim-photorealistic` (`specializations/robotics-simulation/isaac-sim-photorealistic`) | Isaac Sim Photorealistic Simulation - Build GPU-accelerated photorealistic simulation environment |
| `lidar-mapping-localization` (`specializations/robotics-simulation/lidar-mapping-localization`) | LiDAR-Based Mapping and Localization - Implement 3D LiDAR SLAM for robust localization in |
| `moveit-manipulation-planning` (`specializations/robotics-simulation/moveit-manipulation-planning`) | Manipulation Planning with MoveIt - Configure MoveIt for robotic arm motion planning and |
| `mpc-controller-design` (`specializations/robotics-simulation/mpc-controller-design`) | MPC Controller Design - Design and implement Model Predictive Control for robot trajectory |
| `multi-robot-coordination` (`specializations/robotics-simulation/multi-robot-coordination`) | Multi-Robot Coordination - Implement coordination systems for multiple robots including |
| `nav2-navigation-setup` (`specializations/robotics-simulation/nav2-navigation-setup`) | Nav2 Navigation Stack Setup - Configure ROS 2 Nav2 for autonomous mobile robot navigation |
| `neural-network-edge-optimization` (`specializations/robotics-simulation/neural-network-edge-optimization`) | Neural Network Model Optimization for Edge Deployment - Optimize neural network models for |
| `object-detection-pipeline` (`specializations/robotics-simulation/object-detection-pipeline`) | Object Detection and Recognition Pipeline - Develop perception pipeline for detecting and |
| `path-planning-algorithm` (`specializations/robotics-simulation/path-planning-algorithm`) | Path Planning Algorithm Implementation - Implement and tune path planning algorithms for |
| `rl-robot-control` (`specializations/robotics-simulation/rl-robot-control`) | Reinforcement Learning for Robot Control - Train RL agent for robot control tasks using |
| `robot-bring-up-integration` (`specializations/robotics-simulation/robot-bring-up-integration`) | Robot Bring-Up and Integration Testing - Systematic robot hardware and software bring-up |
| `robot-calibration` (`specializations/robotics-simulation/robot-calibration`) | Robot Calibration Workflow - Systematic calibration of robot sensors, actuators, and kinematic |
| `robot-fleet-management` (`specializations/robotics-simulation/robot-fleet-management`) | Robot Fleet Management System - Develop comprehensive fleet management for multiple robots |
| `robot-system-design` (`specializations/robotics-simulation/robot-system-design`) | Robot System Design and Requirements - Define comprehensive requirements and design specifications |
| `robot-urdf-sdf-model` (`specializations/robotics-simulation/robot-urdf-sdf-model`) | Robot URDF/SDF Model Creation - Create accurate robot models in URDF/SDF format for simulation |
| `safety-system-validation` (`specializations/robotics-simulation/safety-system-validation`) | Safety System Validation and Certification - Comprehensive validation of robot safety systems |
| `sensor-fusion-framework` (`specializations/robotics-simulation/sensor-fusion-framework`) | Sensor Fusion Framework - Implement multi-sensor fusion for robust state estimation including |
| `sim-to-real-transfer` (`specializations/robotics-simulation/sim-to-real-transfer`) | Sim-to-Real Transfer Validation - Validate and optimize transfer of policies and models from |
| `simulation-performance-optimization` (`specializations/robotics-simulation/simulation-performance-optimization`) | Simulation Performance Optimization - Optimize simulation speed and scalability for large-scale |
| `synthetic-data-pipeline` (`specializations/robotics-simulation/synthetic-data-pipeline`) | Synthetic Data Generation Pipeline - Automated pipeline for generating synthetic training data |
| `trajectory-optimization` (`specializations/robotics-simulation/trajectory-optimization`) | Trajectory Optimization - Implement trajectory optimization for smooth and efficient robot |
| `visual-slam-implementation` (`specializations/robotics-simulation/visual-slam-implementation`) | Visual SLAM Implementation - Implement and tune visual SLAM system for robot localization |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `robotics-simulation` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
