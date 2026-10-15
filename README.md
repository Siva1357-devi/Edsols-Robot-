# Jetson Nano Autonomous Robot

## Project Overview

This project is a two-wheel autonomous robotic vehicle developed using the NVIDIA Jetson Nano. The robot is designed to navigate its surroundings using computer vision and sensors.

The system focuses on road/line following, obstacle detection, and collision avoidance to enable safe and autonomous movement.

## Objectives

- Develop an autonomous two-wheel robotic vehicle
- Implement road/line following
- Detect obstacles in the robot's path
- Avoid possible collisions
- Understand AI-based robotic navigation
- Integrate hardware and software for real-time operation

## Hardware Used

- NVIDIA Jetson Nano
- Two-wheel robotic chassis
- DC motors
- Motor driver
- Camera
- Ultrasonic/obstacle detection sensor
- Battery
- Connecting wires

## Technologies Used

- Python
- OpenCV
- Computer Vision
- NVIDIA Jetson Nano
- Robotics
- Embedded Systems
- AI-based Navigation

## Key Features

### 1. Road Following

The camera captures the road or line in front of the robot. The image is processed using computer vision techniques to identify the path and control the movement of the robot.

### 2. Obstacle Detection

The robot continuously monitors its surroundings for obstacles. When an obstacle is detected in its path, the system takes appropriate action.

### 3. Collision Avoidance

The robot can change its direction or stop when an obstacle is detected, helping to prevent collisions.

### 4. Autonomous Navigation

The robot can move and navigate with minimum manual control by combining camera-based vision and sensor information.

## Working Principle

The camera captures real-time images of the environment. The NVIDIA Jetson Nano processes the captured data using Python and computer vision techniques.

The system identifies the road/line and determines the required movement of the robot. At the same time, obstacle detection is performed to identify objects in the robot's path.

Based on the detected road and obstacles, the Jetson Nano sends control commands to the motor driver, which controls the two DC motors.

## Applications

- Autonomous vehicles
- Robotics research
- Smart transportation
- Educational robotics
- AI-based navigation
- Obstacle avoidance systems
- Autonomous delivery robots

## Learning Outcomes

Through this project, I gained practical knowledge of:

- NVIDIA Jetson Nano
- Python programming
- OpenCV and computer vision
- DC motor control
- Motor driver interfacing
- Obstacle detection
- Collision avoidance
- Road/line following
- Autonomous robot navigation
- Hardware and software integration
