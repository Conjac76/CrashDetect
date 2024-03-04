Gyroscopic Incident Detection System

Introduction

This project is a Gyroscopic Incident Detection System designed to detect incidents such as falls 
or sudden movements using an MPU6050 accelerometer and gyroscope module. The system utilizes an Arduino 
microcontroller to process sensor data and trigger alerts in case of an incident.


Setup
To set up the circuit, follow these steps (Diagram shown in SetUp.png). All of these items 
can be found in the kit given in engineering 101. Or can be sourced at the chapman
maker space. 

Components Needed:

Arduino microcontroller board (e.g., Arduino Uno)
MPU6050 accelerometer and gyroscope module
16x2 LCD display
Resistors and jumper wires as required
Circuit Connections:

Connect the MPU6050 module to the Arduino board according to the diagram shown in SetUp.png.
Connect the 16x2 LCD display to the Arduino board using appropriate connections.
Software Installation:

Install the necessary libraries for the project by including the following libraries in your Arduino IDE:
Adafruit_MPU6050: Adafruit MPU6050 Library
LiquidCrystal: Standard Arduino Library
Arduino Sketch:

Copy and paste the provided Arduino sketch (incident_detection.ino) into your Arduino IDE.
Upload the sketch to your Arduino board.
Usage
Once the circuit is set up and the Arduino sketch is uploaded, the Gyroscopic Incident Detection System 
will start monitoring for incidents. The system detects sudden movements or falls using the MPU6050 
accelerometer and triggers an alert on the connected LCD display.

Contributing
Contributions to this project are welcome! Please refer to the CONTRIBUTING.md file for guidelines on how to contribute.
