
# Black-Line-Following-Obstacle-Avoidance-Robot
Features: Real-time line tracking &amp; obstacle avoidance with decision-making algorithms.

 # Project Overview

This project involves designing and developing an autonomous robot capable of navigating a path by following lines and avoiding obstacles in real time. The robot uses microcontrollers, IR sensors for line detection, and ultrasonic sensors for obstacle detection. It implements algorithms for smooth navigation and decision-making, making it ideal for automation and robotics applications.

# Features

Autonomous navigation along predefined paths using IR sensors

Obstacle detection and avoidance using ultrasonic sensors

Real-time decision-making for path correction

Modular and scalable design for robotics experiments

Can be adapted for industrial or research automation projects

# Database

No traditional database is required.

Sensor readings (IR and ultrasonic) are processed in real-time and stored temporarily in microcontroller memory or variables.

Optional logging can be implemented using SD card or serial monitoring for performance analysis.

# Installation / Setup

1. Hardware Components Required:

Microcontroller (Arduino / Raspberry Pi)

IR sensors (for line detection)

Ultrasonic sensors (for obstacle detection)

DC motors with motor driver

Chassis, wheels, and power supply

2. Wiring & Assembly:

Connect IR sensors at the bottom front of the robot for line detection

Mount ultrasonic sensor in front for obstacle detection

Connect motors through the motor driver to microcontroller

3. Software Setup:

Install Arduino IDE (or Raspberry Pi setup)

Upload provided code to the microcontroller

Calibrate sensor thresholds for line and obstacle detection

# Models / Algorithms Used

Line Following Algorithm:

Uses IR sensors to detect line position

Simple proportional controller to correct robot direction

Obstacle Avoidance Algorithm:

Ultrasonic sensor measures distance to obstacles

Decision logic to stop, turn, or bypass obstacles

Optional enhancements: PID controller for smoother line following

# Results / Outcomes

Successfully follows black lines on various surfaces

Detects and avoids obstacles in real-time

Provides a hands-on learning experience in embedded systems, robotics, and sensor integration

Demonstrates automation, control logic, and basic AI decision-making in robotics


![Sample photo](https://github.com/user-attachments/assets/e107cf2d-d7fc-4f4b-8308-0482c2a4c96f)
