# ESP32 Analog Read - Potentiometer

## Author
SELVASH

## Description
This project reads the analog value from a potentiometer using the ESP32.

The potentiometer is connected to GPIO 34.
The ESP32 ADC reads values from 0 to 4095.

The value is displayed in the Serial Monitor every 500 milliseconds.

## Components
- ESP32 DevKit
- Potentiometer

## Connections

| Potentiometer | ESP32 |
|---|---|
| VCC | 3.3V |
| GND | GND |
| SIG | GPIO 34 |

## Working
1. The potentiometer gives an analog voltage.
2. ESP32 reads the voltage through GPIO 34.
3. The ADC converts it to a value from 0 to 4095.
4. The value is printed in the Serial Monitor.
5. The reading is updated every 500 ms.

## Files
- sketch.ino
- diagram.json
- README.md

## Simulator
Wokwi Simulator:
https://wokwi.com/projects/476925336166903809

## Author
SELVASH
