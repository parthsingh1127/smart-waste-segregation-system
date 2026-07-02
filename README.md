# BINDASS – AI-Based Smart Waste Segregation System ♻️

An intelligent waste segregation system that combines embedded systems, computer vision, and automation to classify and sort waste with minimal human intervention.

---

## Overview

BINDASS is a smart waste segregation system developed to automate the process of separating different types of waste. The project integrates sensors, computer vision, and embedded hardware to identify waste materials and direct them into the appropriate collection bins using an automated sorting mechanism.

The goal of the project is to improve waste management efficiency, reduce manual effort, and promote sustainable disposal practices.

---

## Features

* Automated waste classification
* Computer vision-based object detection
* Sensor-assisted material identification
* Servo-driven sorting mechanism
* Modular hardware architecture
* Real-time processing and decision making
* Expandable design for additional waste categories

---

## Hardware Used

* Arduino Uno
* Raspberry Pi 5
* Camera Module
* IR Sensor
* Moisture Sensor
* Metal Detection Sensor
* Servo Motors
* LM2596 Buck Converter
* Conveyor and Mechanical Sorting Assembly

---

## Software & Technologies

* C++
* Python
* OpenCV
* Arduino IDE
* Raspberry Pi OS
* Embedded Systems Programming

---

## Working Principle

1. Waste is placed onto the conveyor.
2. Sensors collect information about the material.
3. The camera captures an image of the object.
4. Computer vision analyzes the object.
5. The controller determines the waste category.
6. Servo motors direct the object into the corresponding collection bin.

---

## System Architecture


Waste Input
      │
      ▼
Sensor Data + Camera Image
      │
      ▼
Raspberry Pi (Computer Vision)
      │
      ▼
Decision Logic
      │
      ▼
Arduino Controller
      │
      ▼
Servo Actuation
      │
      ▼
Sorted Waste Bin
``

--

## Repository Structure

text
.
├── ai/
├── cad/
├── docs/
├── firmware/
├── hardware/
├── images/
├── raspberry_pi/
├── README.md
└── LICENSE
``

--

## Project Highlights

* Integrated embedded electronics with computer vision.
* Designed a modular automation system for waste segregation.
* Combined hardware, software, and mechanical design into a single working prototype.
* Built with scalability in mind for future enhancements.

---

## Future Improvements

* Train a custom AI model for improved classification accuracy.
* Add cloud-based monitoring and analytics.
* Integrate IoT for remote monitoring.
* Improve conveyor speed optimization.
* Expand support for additional waste categories.

---

## Contributors

**Parth Singh**

---

## License

This project is licensed under the MIT License.

