# Automated Irrigation Controller (Actuator Logic)

## Project Overview

This project uses an ESP32, a potentiometer (to simulate a soil moisture sensor), and a relay module to automate irrigation.

When the soil is dry, the ESP32 turns the relay ON (simulating a water pump). When the soil is wet, the relay turns OFF.

## Components Used

- ESP32
- Potentiometer (Soil Moisture Sensor Simulation)
- Relay Module
- Jumper Wires
- Wokwi Simulator

## Circuit Connections

| Component | ESP32 |
|----------|--------|
| Potentiometer VCC | 3V3 |
| Potentiometer GND | GND |
| Potentiometer SIG | GPIO 34 |
| Relay VCC | VIN / 5V |
| Relay GND | GND |
| Relay IN | GPIO 26 |

## Working

1. ESP32 reads the soil moisture value.
2. If the value is greater than 2000, the soil is considered dry.
3. The relay turns ON to simulate the water pump.
4. If the value is less than or equal to 2000, the relay turns OFF.

## Example Output

Soil Moisture Value: 2500

Soil is Dry - Pump ON

## Wokwi Simulation

https://wokwi.com/projects/467998354020827137

## Author

Fathima Nazrin

Decode Labs Internship