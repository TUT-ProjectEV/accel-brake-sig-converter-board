# accel-brake-sig-converter-board

## Overview
- This board converts the sensor output VOLTAGE signal into the CURRENT signal
    - 4~20mA

## Requirement
### Development
- Kicad 8.0
### Libraries
- ProjectEV-Kicad-Library
    - v8.0

## Usage
- J1, J2, J3: Connect to Controller or ADC and Power supply
    - Pin 1: +12V Input
    - Pin 2: GND
    - Pin 3: Current Signal Output
- J4, J5, J6: Connect to Sensor
    - Pin 1: +5V Output
    - Pin 2: GND
    - Pin 3: Voltage Signal Input

## Features
- Input Signal Voltage Range: +1~+5V
- Output Signal Current Range: 4~20mA
    - 250 Ohms termination: +1~+5V

## Reference
- ["Reference Site Name"]("Reference URL")

## Author
- [ST04-tkmr](https://github.com/ST04-tkmr)

## License
- Copyright (c) 2024 東京工科大学 ProjectEV
