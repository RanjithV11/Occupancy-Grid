# Occupancy-Grid
Infrastructure Camera-Based 2D Occupancy Grid Mapping for AMR Navigation
Project Overview
This project aims to develop a system for real-time indoor environment mapping using a network of overhead RGB cameras. The system enhances Autonomous Mobile Robot (AMR) navigation by providing accurate 2D occupancy grid maps. The project involves simulating the environment in Gazebo, calibrating multiple cameras, fusing their images, and evaluating the resulting maps for accuracy and computational efficiency.

Features
Real-Time Mapping: Utilizes a network of RGB cameras arranged in a 2x2 matrix for real-time indoor environment mapping.
Gazebo Simulation: Implements a simulated environment with four overhead cameras, each providing a bird's-eye view.
Multi-Camera Calibration: Includes techniques for automatic calibration and alignment of the cameras' fields of view.
Map Fusion: Combines images from multiple cameras to create a comprehensive 2D occupancy grid map.
ROS Integration: Ensures compatibility of the generated maps with the ROS navigation stack.
Performance Evaluation: Benchmarks the accuracy of the fused map against the Gazebo ground truth and measures computational latency.
