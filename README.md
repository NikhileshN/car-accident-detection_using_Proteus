# IoT-Based Smart Vehicle Safety and Accident Monitoring System

This repository contains the design, implementation, and simulation files for the project titled "IoT-Based Smart Vehicle Safety and Accident Monitoring System." The project aims to enhance vehicular safety using an intelligent accident detection system integrated with various sensors and communication modules. It provides immediate alerts with location data in case of accidents or hazardous conditions.

## Overview

The system is designed using a combination of Raspberry Pi, Arduino, and various sensors including:
- ADXL345 Accelerometer
- SW-420 Vibration Sensor
- MQ-7 Carbon Monoxide Gas Sensor
- NEO-6M GPS Module
- SIM800A GSM Module
- LDR for ambient light detection
- Raspberry Pi Camera for image capture

The system detects accidents or gas leaks and sends alert messages to a predefined mobile number with GPS coordinates. It also features an automatic light dimming and dipping mechanism for night driving safety using an LDR sensor.

## Project Files

- `acc.pdsprj`: Proteus project file for simulation
- `arduino_code.ino`: Arduino sketch for interfacing MQ-7 and vibration sensors
- `raspberry_pi_code.py`: Python script for Raspberry Pi logic including LCD handling and accident detection
- `project_report.pdf`: Detailed documentation of the system design, implementation, and results (if uploaded)
- `images/`: Optional folder to include hardware or simulation screenshots

## How to Run

To simulate the system:
1. Open Proteus 8.15 or later.
2. Load the file `acc.pdsprj`.
3. Run the simulation to observe the accident detection and monitoring system behavior.

To run the hardware code:
1. Upload the `arduino_code.ino` to the Arduino UNO.
2. Ensure Raspberry Pi is set up with required libraries and run `raspberry_pi_code.py`.
3. Ensure connections to all sensors and modules are as per the block diagram included in the report.

## Features

- Accident detection using vibration and accelerometer sensors
- Gas leakage detection using MQ-7 sensor
- Real-time location tracking with GPS
- GSM-based alert message with coordinates
- Visual output using LCD
- Automatic headlight dimming using LDR
- Proteus simulation to validate sensor response and system logic

## Software Requirements

- Proteus 8.15 or later
- Arduino IDE 2.1.1
- Python 3.x with RPi.GPIO and smbus libraries
- Raspberry Pi OS with terminal access
- Raspberry Pi Imager for OS installation

## Hardware Components

- Raspberry Pi 3B+
- Arduino UNO
- ADXL345 Accelerometer
- SW-420 Vibration Sensor
- MQ-7 Gas Sensor
- NEO-6M GPS Module
- SIM800A GSM Module
- 5MP Raspberry Pi Camera
- LED and LDR components
- LCD display

## Note to Repository Visitors

To simulate the system, open the Proteus project file `acc.pdsprj` and run the simulation using Proteus 8.15 or later.

## License

This project is submitted as part of an academic requirement. Please contact the supervising institution for permissions related to reuse or modification.
