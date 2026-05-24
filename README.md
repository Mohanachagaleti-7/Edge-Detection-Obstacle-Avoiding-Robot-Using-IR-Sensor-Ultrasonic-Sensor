# Edge-Detection-Obstacle-Avoiding-Robot-Using-IR-Sensor-Ultrasonic-Sensor
The Edge Detection &amp; Obstacle Avoiding Robot is an autonomous robot developed using Arduino UNO, IR Sensor, Ultrasonic Sensor, L293D Motor Driver, and ESP8266 Wi-Fi Module.

The robot uses an IR sensor to detect edges and prevent falling from surfaces like stairs or tables. The Ultrasonic Sensor detects nearby obstacles and helps the robot avoid collisions automatically.

The Arduino UNO processes the sensor data and controls the DC motors through the motor driver. The ESP8266 module sends real-time sensor data to the ThingSpeak cloud platform for IoT monitoring and graphical visualization.

This project provides a low-cost, reliable, and smart solution for autonomous navigation and robotic applications.
# Project Overview

The Edge Detection & Obstacle Avoiding Robot is an autonomous robotic system designed using Arduino UNO, IR Sensor, Ultrasonic Sensor, L293D Motor Driver, and ESP8266 Wi-Fi Module.

The robot is capable of:

. Detecting edges and preventing falls
. Detecting obstacles and avoiding collisions
. Moving automatically without human control
. Sending real-time sensor data to the cloud using Iot.
# Objectives
. To develop an autonomous robot using Arduino UNO
. To detect obstacles using an ultrasonic sensor
. To detect edges using IR sensors
. To avoid collisions and falling from edges
. To control DC motors using an L293D motor driver
. To send sensor data to the cloud using ESP8266
. To implement real-time monitoring using ThingSpeak
# Features

. Edge detection using IR sensor

. Obstacle avoidance using ultrasonic sensor

. Autonomous robot movement

. Real-time distance measurement

. IoT cloud monitoring using ThingSpeak

. Wireless communication using ESP8266

. Safe and reliable navigation

. Low-cost robotic system

. Real-time graphical data visualization
# Components
## 🛠️ Hardware Components:
1.Arduino UNO
2.Ultrasonic Sensor (HC-SR04)
3.IR Sensor
4.L293D Motor Driver
5.DC Geared Motors
6.Robot Wheels
7.ESP8266 Wi-Fi Module
8.12V Rechargeable Battery
9.Robot Chassis
10.Jumper Wires
11.Power Supply Module
## 💻 Software Components:
1.Arduino IDE
2.Embedded C Programming
3.ThingSpeak Cloud Platform
4.Tinkercad Simulation Software
# Working Principle

The Edge Detection & Obstacle Avoiding Robot works using both IR Sensor and Ultrasonic Sensor for safe automatic navigation.

The IR sensor detects edges or sudden surface changes such as stairs and table edges. When an edge is detected, the Arduino stops the robot and changes its direction to prevent falling.

The Ultrasonic Sensor detects nearby obstacles by measuring the distance between the robot and objects. If an obstacle is detected, the robot automatically stops and turns to avoid collision.

The Arduino UNO processes the sensor data and controls the DC motors through the L293D motor driver. The ESP8266 Wi-Fi module sends sensor data to the ThingSpeak cloud platform for real-time monitoring.

Thus, the robot can move automatically, avoid obstacles, prevent falling, and provide IoT-based monitoring.
# ☁️ ThingSpeak Cloud Monitoring
ThingSpeak is an IoT cloud platform used to:
. Store sensor data
. Generate real-time graphs
. Monitor robot performance remotely

The ESP8266 continuously uploads sensor readings to the cloud.
## 📊 Dashboard Explanation
📈 Field 1 – IR Sensor Graph

This graph displays the IR sensor values used for edge detection.

Graph Interpretation:
Value changes when edge is detected
Helps monitor edge detection activity
Indicates safe or unsafe surface conditions

When the robot reaches an edge:

Sensor value changes
Arduino stops the robot
Robot changes direction automatically

📉 Field 2 – Ultrasonic Distance Graph

This graph shows the distance measured by the ultrasonic sensor.

Graph Interpretation:
High value → Object is far away
Low value → Object is near

When an obstacle comes close:

Robot stops
Changes path
Avoids collision

This graph helps analyze obstacle detection performance in real-time.
# Complete System Workflow
Step 1: Sensor Data Collection
IR sensor checks edges
Ultrasonic sensor measures distance

Step 2: Arduino Processing
Arduino reads sensor inputs
Processes conditions using programmed logic

Step 3: Motor Control
L293D driver controls motor movement
Robot moves safely based on sensor data

Step 4: IoT Communication
ESP8266 sends sensor data to ThingSpeak cloud

Step 5: Real-Time Monitoring
ThingSpeak displays graphs
Users monitor robot performance remotely
# Circuit Connections

🔴 Ultrasonic Sensor (HC-SR04)
VCC → 5V
GND → GND
TRIG → D3
ECHO → D4

⚫ IR Sensor
VCC → 5V
GND → GND
OUT → D9

🟩 L293D Motor Driver
IN1 → D5
IN2 → D6
IN3 → D7
IN4 → D8
VCC → 5V
GND → GND
12V Input → Battery

 DC Motors
Motor 1 → OUT1 & OUT2
Motor 2 → OUT3 & OUT4

 ESP8266 Wi-Fi Module
VCC → 3.3V
GND → GND
TX → RX of Arduino
RX → TX of Arduino

🔋 Battery
Positive → Motor Driver 12V Input
Negative → GND.
# Advantages

. Prevents robot from falling

.  Avoids obstacle collisions

. Real-time monitoring support

. Autonomous operation

. Low-cost implementation

. Reliable navigation

. Easy to build and maintain

. Supports IoT applications
# Applications
🤖 Robotics Research

Used for autonomous robotic navigation experiments.

🏭 Industrial Inspection

Useful in dangerous or inaccessible areas.

🛡️ Surveillance Systems

Can monitor environments automatically.

📦 Warehouse Automation

Supports automatic movement systems.

🎓 Educational Projects

Useful for learning Embedded Systems and IoT.
# Future Scope
. Add AI-based decision making

. Integrate camera module

. Add GPS tracking system

. Mobile app control

. Voice-controlled navigation

. Machine learning integration

. Advanced obstacle detection
# Results

The project was successfully implemented and tested.


. Accurate edge detection using IR sensor

. Successful obstacle avoidance using ultrasonic sensor

. Smooth autonomous navigation

. Real-time IoT monitoring through ThingSpeak

. Reliable motor control using L293D

. Efficient data transmission using ESP8266

The robot responded quickly to environmental changes and safely navigated without collisions or falling from edges.
# Conclusion

The Edge Detection & Obstacle Avoiding Robot is a smart autonomous robotic system that combines:

Embedded Systems
Robotics
Sensor Technology
IoT Communication

The robot successfully detects edges and obstacles, preventing accidents and ensuring safe navigation. The integration of ESP8266 and ThingSpeak enables real-time cloud monitoring and improves system intelligence.

This project demonstrates a cost-effective and reliable solution for autonomous robotic applications and serves as an excellent project for Embedded Systems, IoT, and Robotics learning.
