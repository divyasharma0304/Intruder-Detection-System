# Intruder Detection System

This project is a real-time intruder detection system designed to alert the property owner of any unauthorized access attempts. The system uses an MSP430 microcontroller, an IR sensor, and additional components to detect and signal the presence of an intruder by activating a buzzer and turning on an indicator light. 

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Code](#code)
- [Learning Outcomes](#learning-outcomes)
- [Contributors](#contributors)

## Overview
The Intruder Detector System is built to enhance security by automatically detecting any unauthorized entry attempts. When an intruder is detected, the system activates an alarm (buzzer) and turns on a light to alert the property owner. The detection system is displayed on an LCD screen, providing real-time feedback.

## Features
- **Intruder Detection**: Uses an IR sensor to detect the presence of unauthorized personnel.
- **Alarm System**: Activates a buzzer and indicator light to signal the detection.
- **LCD Display**: Provides real-time status updates on the detection system.
- **Manual Control**: The system can be manually turned ON or OFF by the owner.

## Project Structure
- **Microcontroller**: MSP430 LunchBox, which serves as the control center of the detection system.
- **Sensors and Actuators**: IR sensor for detection, relay module to activate the light and buzzer.
- **Display**: LCD screen for displaying system status.
- **Circuit Components**: LEDs, resistors, jumper wires, and breadboard.

## Hardware Requirements
1. **MSP430 LunchBox with USB Cable**
2. **IR Sensor Module**: Detects intruder presence.
3. **Relay Module**: Controls power to the alarm system.
4. **LEDs and Resistors**: Indicator lights for visual alert.
5. **LCD Display**: Shows detection status.
6. **Buzzer**: Audible alert for intruder detection.
7. **Breadboard, Jumper Wires, Potentiometer**: For building the circuit.

## Software Requirements
1. **Code Composer Studio**: Used for programming the MSP430 microcontroller.
2. **C/C++ Programming Knowledge**: Required to understand and modify the code if necessary.

## Installation
1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/yourusername/Intruder-Detector-System.git
    cd Intruder-Detector-System
    ```
2. Connect the MSP430 and other components as per the schematic in the project report.
3. Open `code.cpp` in Code Composer Studio, compile, and upload it to the MSP430 microcontroller.

## Usage
1. After uploading the code, power on the system.
2. When an intruder is detected, the IR sensor sends a signal to the MSP430, triggering the relay to activate the buzzer and turn on the indicator light.
3. The LCD display will update the status in real-time.
4. To reset the system, turn it OFF and then ON again.

## Code
- The main code file for this project is [`code.cpp`](code.cpp), which contains:
  - Functions for setting up the IR sensor, relay, and LCD.
  - Logic to control the detection, alert, and display systems.

## Learning Outcomes
Through this project, we learned:
- How to work with Code Composer Studio for microcontroller programming.
- Techniques for integrating sensors (IR and relay modules) and actuators (buzzer, LED).
- Circuit design and wiring for security applications.
