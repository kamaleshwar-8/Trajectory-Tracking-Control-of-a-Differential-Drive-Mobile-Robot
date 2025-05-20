# Overview
This repository contains the implementation of a robust hybrid control strategy for improved trajectory tracking in differential-drive mobile robots. The system combines adaptive PID control with swarm intelligence optimization techniques and a disturbance observer to enhance trajectory tracking performance in uncertain environments.
The video in this repository shows the TurtleBot3 running with our implemented controller.

# Key Features

Adaptive PID Control: Real-time adjustment of PID gains to adapt to changing environmental conditions.
Swarm Intelligence Optimization: Implementation of Grey Wolf Optimization (GWO) and Slime Mould Algorithm (SMA) for PID gain tuning..
Disturbance Observer: Luenberger observer implementation to estimate unmeasurable states and counteract both additive and multiplicative noise
Comprehensive Validation: Both simulation (ROS2-Gazebo) and real hardware validation on TurtleBot3.
