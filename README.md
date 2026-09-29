# Line-Follower-Robot

Built an autonomous line-following robot using 7 IR sensors and PID control to detect and follow black paths on a white surface. Implemented sensor calibration, adaptive speed control, real-time steering correction, and line-loss recovery for accurate navigation.

# Project Overview

The Line-Follower Robot is an autonomous robotic system designed to detect and follow a predefined path using IR sensors. The robot continuously reads the surface through multiple sensors and uses PID-based control to calculate the deviation from the path and adjust the motor speeds accordingly.

The implementation includes sensor calibration, real-time steering correction, adaptive speed control, and line-loss recovery, allowing the robot to follow paths with improved stability and accuracy.

# Technologies / language
C++ • Arduino • IR Sensors • PID Control • TB6612 Motor Driver

# What the project actually does

The project includes:

7 IR/analog sensors for detecting the line.
Automatic sensor calibration before operation.
PID control using:
Proportional (P)
Integral (I)
Derivative (D)
Dynamically adjusts left and right motor speeds according to the detected error.
Supports black-line and white-line configurations.
Supports 5 or 7 sensors through configuration.
Includes line-loss detection and recovery.
Uses TB6612 motor control through the SparkFun library.
Includes configurable line thickness and braking behavior.
Gradually increases the robot's speed up to the configured maximum.

# Applications
 1. Industrial Automation – Automated movement of robots along predefined factory routes.

 2. Warehouse Automation – Transportation of materials and packages between designated locations.

 3. Hospital Automation – Autonomous transportation of medicines and supplies.

 4. Educational Robotics – Learning sensors, motors, embedded systems, and control algorithms.

 5. Robotics Competitions – Line-following and autonomous navigation challenges.
