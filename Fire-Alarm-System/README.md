# Fire Alarm System with Email Alerts

An ESP32-based fire detection system using an infrared flame sensor and LED with real-time email alerts.

## Description

The infrared flame sensor detects infrared radiation emitted by flames. When a high flame-sensor signal is detected, the ESP32 activates an LED and sends an email alert to the recipient.

## Components

- ESP32
- Infrared Flame Sensor
- LED
- Jumper Wires
- Breadboard

## Working

1. The flame sensor continuously detects infrared radiation.
2. The ESP32 reads the sensor output.
3. When a high flame signal is detected, the ESP32 turns on the LED.
4. The system sends an email notification to the configured recipient.

## Technologies

- ESP32
- Arduino IDE
- Embedded C/C++
- Flame Sensor
- Email Notification

## Project Output

The system provides both local LED indication and email notification when a flame is detected.
