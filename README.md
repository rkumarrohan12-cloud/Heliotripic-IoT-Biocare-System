# 🌱 Heliotropic IoT BioCare System

## 📌 Overview
This project is an IoT-based smart plant system that automatically rotates a plant towards the direction of maximum sunlight using LDR sensors and a stepper motor.

## ⚙️ Components Used
- Arduino UNO
- Stepper Motor
- Stepper Driver
- 4 LDR Sensors
- Lithium-ion Battery (3x 3.7V in series)
- BMS (Battery Management System)

## 🧠 Working Principle
Four LDR sensors are placed at 90° to each other forming a square layout. The system continuously compares light intensity from all sensors and rotates the plant towards the direction of maximum light.

## 📱 UI/UX
The UI is designed using Figma and displays:
- Light direction
- Sensor values
- Motor status
- Battery level

## 🔌 Future Scope
- Mobile App Integration
- WiFi-based monitoring (ESP8266/ESP32)
- Data logging and analytics

