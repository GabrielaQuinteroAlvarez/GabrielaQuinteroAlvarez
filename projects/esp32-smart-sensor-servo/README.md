# ESP32 Smart Sensor & Servo System

## Overview
This embedded-systems project uses an **ESP32 NodeMCU-32S** to read several sensors and control a servo motor and multiple LEDs in real time.

The system combines analog sensing, threshold logic, PWM output, actuator control, and serial monitoring in one microcontroller application.

## Hardware
- ESP32 NodeMCU-32S
- Servo motor
- Distance sensor
- Light sensor
- Touch sensor
- Temperature sensor
- Status LEDs
- 330 Ω LED resistors
- 10 kΩ sensor resistors
- Transistor circuitry

## Pin Configuration
| Function | ESP32 Pin |
|---|---:|
| Servo | GPIO 23 |
| Distance Sensor | GPIO 35 |
| Light Sensor | GPIO 36 |
| Touch Sensor | GPIO 34 |
| Temperature Sensor | GPIO 39 |
| Touch LED | GPIO 25 |
| Light LED | GPIO 32 |
| PWM LED | GPIO 22 |
| Temperature LED | GPIO 33 |

## System Behavior
- Maps distance-sensor readings to a servo position from 0° to 180°
- Reads ambient light and controls LED behavior using a dead-zone
- Uses PWM to vary LED brightness
- Detects touch using an analog threshold
- Compares temperature readings against a startup baseline
- Prints live sensor values through the Serial Monitor
- Includes behavior modifications for motion detection and output logic

## What I Learned
This project strengthened my understanding of:
- Analog sensor calibration
- ESP32 GPIO configuration
- PWM
- Servo control
- Threshold-based logic
- Embedded C/C++
- Hardware debugging
- Power and USB troubleshooting
- Integrating multiple sensors into one system

## Tools
**Arduino IDE · ESP32Servo · C/C++ · ESP32**

## Portfolio Note
Course starter material is not reproduced here. Only personally written or course-approved code should be added publicly.
