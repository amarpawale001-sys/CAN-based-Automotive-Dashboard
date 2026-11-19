# CAN Automotive Dashboard

## Project Description
Developed a CAN-based automotive dashboard using Embedded C and PIC18F4580 microcontrollers. Three ECUs communicate through the CAN protocol to monitor and display vehicle parameters on an LCD.

## Features
- Displays vehicle speed.
- Displays gear position.
- Displays engine RPM.
- Controls left and right indicators.
- Displays indicator status on the dashboard.
- Enables communication between three ECUs using CAN protocol.

## Hardware Requirements
- PIC18F4580 Microcontrollers (3)
- CAN Transceiver Modules
- Character LCD (CLCD)
- Potentiometers
- Push Buttons
- LEDs

## Software Requirements
- MPLAB X IDE
- XC8 Compiler
- Embedded C

## Technologies Used
- Embedded C
- PIC18F4580
- CAN Protocol
- ADC
- GPIO
- Timers
- CLCD

## Working Principle
The project uses three ECUs connected through CAN communication.

- **ECU 1:** Reads vehicle speed and gear position and transmits the data.
- **ECU 2:** Reads engine RPM and indicator inputs and transmits the data.
- **ECU 3:** Receives data from both ECUs and displays vehicle information on the LCD.

## Learning Outcomes
- Understanding CAN communication between multiple ECUs.
- Working with microcontroller peripherals.
- Implementing data transmission and reception using CAN protocol.
- Displaying real-time vehicle information on an LCD.

## Author
**Amarnath Pawale**

[GitHub Profile](https://github.com/amarpawale001-sys)
