# Smart Environmental Monitor

## Project Overview
This project is a Smart Environmental Monitor created using an ESP32 microcontroller and a DHT22 temperature and humidity sensor.

The system reads the surrounding temperature and humidity every 2 seconds and displays the values in the Serial Monitor.

## Components Used
- ESP32 Development Board
- DHT22 Temperature and Humidity Sensor
- Jumper Wires
- Wokwi Online Simulator

## Circuit Connections
| DHT22 Pin | ESP32 Pin |
|---|---|
| VCC | 3V3 |
| DATA | GPIO 15 |
| GND | GND |

## Working
1. The DHT22 sensor measures temperature and humidity.
2. The ESP32 receives the sensor data through GPIO 15.
3. The program prints temperature and humidity in the Serial Monitor.
4. The process repeats every 2 seconds.

## Output
The Serial Monitor displays temperature in degree Celsius and humidity in percentage.

Example:
```text
Temperature: 30.0 °C
Humidity: 65.0 %


Simulation Link
https://wokwi.com/projects/467819194129500161
Author
Fathima Nazrin
Decode Labs Internship