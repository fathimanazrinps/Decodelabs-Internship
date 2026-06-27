# Cloud-Connected Security Node (IoT Telemetry)

## Project Overview
This project uses an ESP32 and an HC-SR04 Ultrasonic Sensor to detect nearby objects. When an object comes within 20 cm, the ESP32 detects it as an intruder and displays an alert in the Serial Monitor.

## Components Used
- ESP32
- HC-SR04 Ultrasonic Sensor
- Jumper Wires
- Wokwi Simulator

## Circuit Connections

| HC-SR04 | ESP32 |
|----------|--------|
| VCC | VIN / 5V (or 3V3 in Wokwi) |
| GND | GND |
| TRIG | GPIO 5 |
| ECHO | GPIO 18 |

## Working

1. ESP32 sends an ultrasonic pulse.
2. The HC-SR04 measures the distance.
3. If the distance is less than 20 cm, the ESP32 prints **"Intruder Detected!"**.
4. Otherwise, it prints **"Area Safe"**.

## Example Output

Distance: 10 cm

Intruder Detected!

## Wokwi Simulation

https://wokwi.com/projects/468001432756615169

## Author

Fathima Nazrin 

Decode Labs Internship