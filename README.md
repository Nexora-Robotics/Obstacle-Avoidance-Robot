<div align="center">

# 🤖 Sentinel

### Autonomous Obstacle Avoidance Robot

<img src="images/robot_top.jpg" width="850">

### Developed by Nexora Robotics

**Engineering Intelligent Machines.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Arduino](https://img.shields.io/badge/Arduino-UNO-00979D)
![Language](https://img.shields.io/badge/Language-C%2B%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

**Sentinel** is a four-wheel autonomous mobile robot capable of detecting and avoiding obstacles using ultrasonic sensing and servo-based environmental scanning. Built around the Arduino Uno, it demonstrates autonomous navigation, embedded control, and practical robotics engineering.

</div>

---

# Project Overview

Sentinel continuously scans its surroundings using an HC-SR04 ultrasonic sensor mounted on an SG90 servo motor. During normal operation the robot moves forward while monitoring the distance ahead. When an obstacle is detected, it reverses briefly, scans the environment to the left and right, compares the available space, and automatically selects the safest direction before continuing.

---

# Features

* Autonomous obstacle avoidance
* Servo-based environmental scanning
* Four-wheel differential drive
* Forward, reverse, left, and right movement
* Real-time ultrasonic distance measurement
* Modular Arduino-based design
* Open-source hardware and software

---

# Hardware Specifications

| Component                 | Quantity |
| ------------------------- | -------: |
| Arduino Uno               |        1 |
| L298N Motor Driver        |        1 |
| TT DC Motor               |        4 |
| HC-SR04 Ultrasonic Sensor |        1 |
| SG90 Servo Motor          |        1 |
| 7.4V Battery              |        1 |
| Robot Chassis             |        1 |

---

# Working Principle

```text
Start
   │
Move Forward
   │
Obstacle Detected?
   │
 ┌─No───────────────┐
 │                  │
Continue Forward    │
 │                  │
 └──────Yes─────────┘
         │
       Stop
         │
   Reverse Briefly
         │
    Scan Left
         │
    Scan Right
         │
 Compare Distances
         │
 Turn Toward Clearer Path
         │
 Continue Forward
```

---

# Folder Structure

```text
Obstacle-Avoidance-Robot
│
├── code/
├── docs/
├── images/
├── videos/
├── README.md
└── LICENSE
```

---

# Repository Contents

* Complete Arduino source code
* Wiring documentation
* Circuit diagram
* Robot images
* Project documentation
* Demonstration video

---

## Gallery

| Top View | Bottom View |
|----------|-------------|
| <img src="images/topside.jpeg" width="400"> | <img src="images/downside.jpeg" width="400"> |
> Replace the filenames above with the actual names of your uploaded images.

---

# Demo

A demonstration video will be added in a future update.

---

# Future Improvements

* PWM motor speed control
* PID-based steering
* Li-ion battery monitoring
* OLED status display
* Bluetooth control
* ESP32 upgrade
* ROS 2 compatibility
* Computer vision integration

---

# Open Source

This project is released under the MIT License.

Contributions, improvements, and educational use are welcome.

---

# About Nexora Robotics

Nexora Robotics is an open-source robotics engineering initiative focused on robotics, embedded systems, artificial intelligence, autonomous navigation, and practical engineering projects.

Our goal is to design intelligent machines, share knowledge openly, and build technologies that create real-world impact.

---

<div align="center">

### Engineering Intelligent Machines.

**Developed with ❤️ by Nexora Robotics**

</div>
