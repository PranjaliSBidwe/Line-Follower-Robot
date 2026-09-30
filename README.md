# Line-Follower-Robot

# Project Overview

The Line-Follower Robot is an autonomous robotic prototype designed to detect and follow a predefined path using multiple IR-based sensors. The system uses seven IR sensors, automatic sensor calibration, PID-based control logic, adaptive motor speed control, and TB6612 motor-driver interfacing to achieve accurate and stable navigation along a marked path.

The robot continuously reads sensor values to determine the position of the line relative to the robot. Based on the detected line position, it calculates the required steering correction and adjusts the speed of the left and right motors accordingly. The system also includes line-loss detection and recovery logic to help the robot regain the path when the line is temporarily lost.

The project demonstrates the integration of embedded programming, analog sensor processing, automatic calibration, PID control, PWM motor control, real-time path detection, adaptive speed adjustment, and autonomous robotic navigation in a single system.

# Hardware Components

The project uses the following major hardware components:

Arduino-Compatible Microcontroller

Seven IR/Line Sensors

TB6612FNG Dual Motor Driver

Two DC Motors

Robot Chassis

Wheels

Power Supply / Battery

Connecting Wires

# Programming Languages & Technologies
C++
Arduino IDE

# Working Flow

1. Power ON – The robot initializes the IR sensors, motor driver, motors, and control pins before starting operation.
2. Automatic Calibration – The robot calibrates the sensors by recording their minimum and maximum readings for reliable line detection.
3. Line Detection – The calibrated sensors continuously detect the position of the line relative to the robot.
4. Line Position Calculation – Sensor readings are processed to determine whether the line is toward the left, center, or right side of the robot.
5. Error Calculation – The difference between the detected line position and the desired center position is calculated as the steering error.
6. PID Control – Proportional, Integral, and Derivative control logic calculates the required correction based on the detected error.
7. Motor Speed Adjustment – The calculated correction is applied to the left and right motors using PWM to control their individual speeds.
8. Adaptive Navigation – Motor speed is adjusted according to the line position and required steering correction for smoother movement.
9. Line-Loss Detection – The robot identifies when the line is temporarily lost and activates the programmed recovery behavior.
10. Path Recovery – The robot adjusts its movement to search for and regain the detected line.
11. Continuous Tracking – The robot repeatedly reads the sensors and updates motor control to autonomously follow the predefined path.

# Applications
 1. Industrial Automation – Automated movement of robots along predefined factory routes.

 2. Warehouse Automation – Transportation of materials and packages between designated locations.

 3. Hospital Automation – Autonomous transportation of medicines and supplies.

 4. Educational Robotics – Learning sensors, motors, embedded systems, and control algorithms.

 5. Robotics Competitions – Line-following and autonomous navigation challenges.
