# Air Pollution Monitoring System
An Arduino-based air pollution and vehicle exhaust monitoring system designed to detect multiple gases and environmental conditions using gas sensors and a temperature/humidity sensor.

## Project Status
PCB Design Completed

## Overview
This project is designed to monitor air pollution using using multiple gas sensors connected to an Arduino Uno.
The system uses gas sensors to detect different pollutants and provides visual and audible indications based on the detected conditions.
Temperature and humidity are also monitored, and the readings can be displayed using an OLED display.
The PCB was designed as a controller and interface board, with the sensor modules connected externally through the provided connections.

## Components
- Arduino Uno
- MQ-7 gas sensor
- MQ-2 gas sensor
- MQ-135 gas sensor
- DHT22 temperature and humidity sensor
- OLED display
- Green LED
- Yellow LED
- Red LED
- Buzzer
- Resistors and supporting components

## Tools Used
- KiCad
- Schematic Editor
- PCB Editor
- 3D Viewer

## Design Process
The PCB was developed through the following stages:
1. Schematic design
2. Electrical Rules Check (ERC)
3. Footprint assignment
4. Component placement
5. Board outline creation
6. PCB routing
7. Copper zone creation
8. Design Rules Check (DRC)

## PCB Design
The completed PCB contains the Arduino interface connections, sensor connections, display connection, indicator LEDs, buzzer, and supporting circuitory.
The external sensor modules are connected to the PCB through their respective headers.

## Project Images
### Schematic
![Schematic](images/air-pollution-schematic)

### PCB Layout
![PCB Layout](images/air-pollution-pcb)

### 3D View
![3D View](images/air-pollution-3d)

## What I Learned
- PCB schematic design
- ERC checking
- Footprint selection and assignment
- PCB component placement
- PCB routing
- Copper zones
- DRC checking
- Designing interfaces for external sensor modules
