🚀 DecodeLabs Internship Portfolio

<div align="center">🌍 ESP32 IoT Projects Collection

Smart Environment Monitoring • Smart Irrigation • Cloud Security

<p align="center">
<img src="https://img.shields.io/badge/ESP32-IoT-blue?style=for-the-badge&logo=espressif">
<img src="https://img.shields.io/badge/Arduino-C++-00979D?style=for-the-badge&logo=arduino">
<img src="https://img.shields.io/badge/Wokwi-Simulator-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Blynk-IoT-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Embedded-Systems-success?style=for-the-badge">
</p>A collection of ESP32-based IoT projects developed during the DecodeLabs Internship, showcasing Smart Automation, Embedded Systems, Cloud Connectivity, and Real-Time Monitoring.

</div>---

📖 About Repository

This repository contains three ESP32-based IoT projects developed during my DecodeLabs Internship. Each project focuses on solving real-world challenges using embedded systems, sensors, automation, and cloud technologies.

The projects were designed and tested using ESP32, Arduino IDE, Wokwi Simulator, and Blynk IoT Platform.

---

🛠️ Tech Stack

Category| Technologies
Controller| ESP32 DevKit
Programming| Arduino C++
IDE| Arduino IDE
Simulator| Wokwi
Cloud Platform| Blynk IoT
Displays| OLED SSD1306, LCD1602 I2C
Sensors| DHT22, HC-SR04, PIR, Soil Moisture
Actuators| Servo Motor, Relay
Indicators| RGB LED, Buzzer

---

📂 Projects Included

Project| Description
🌍 Smart Environment Monitoring System| Real-time environmental monitoring with smart alerts
🌱 IoT-Based Automated Irrigation Controller| Smart irrigation using soil moisture and environmental data
🔐 Cloud Connected Security Node| IoT security system with cloud monitoring and smart access control

---

🌍 Project 1 — Smart Environment Monitoring System

📸 Project Preview

<p align="center">
<img src="IMAGES/environment_monitor.jpg" width="750">
</p>📖 Overview

The Smart Environment Monitoring System continuously monitors temperature, humidity, air quality, and system health using ESP32. It provides real-time data visualization, smart alerts, and automated responses for a safer environment.

✨ Key Features

- 🌡 Real-time Temperature Monitoring
- 💧 Humidity Detection
- 🌫 Air Quality Monitoring
- 📟 OLED Live Display
- 🌈 RGB Status Indicator
- 🔔 Smart Alert System
- ⚙️ Automated Response Mechanism
- 📡 ESP32 Wi-Fi Ready Architecture

🛠️ Hardware Components

- ESP32 Development Board
- DHT22 Sensor
- Gas / Air Quality Sensor
- OLED SSD1306 Display
- RGB LED
- Buzzer
- Servo Motor
- Resistors & Jumper Wires

⚙️ Working Principle

1. Sensors continuously collect environmental data.
2. ESP32 processes the sensor readings in real time.
3. OLED displays live environmental values.
4. RGB LED changes according to the current status.
5. Buzzer activates whenever abnormal conditions are detected.
6. The system continuously monitors and alerts users for improved safety.

🔗 Wokwi Simulation

https://wokwi.com/projects/466689751681985537

---
🌱 Project 2 — IoT-Based Automated Irrigation Controller

📸 Project Preview

<p align="center">
<img src="IMAGES/irrigation_controller.jpg" width="750">
</p>📖 Overview

The IoT-Based Automated Irrigation Controller is a smart agriculture solution that automates irrigation decisions using real-time soil moisture and environmental data. The system minimizes water wastage, improves crop productivity, and promotes sustainable farming through intelligent automation.

✨ Key Features

- 🌱 Automatic Irrigation Control
- 💧 Dual Soil Moisture Monitoring
- 🌡 Temperature & Humidity Monitoring
- 📟 LCD Display Interface
- 📊 OLED Data Visualization
- ⚡ Smart Pump Control Logic
- 🔔 Low Water & Alert Notifications
- 🌍 Sustainable Water Management

🛠️ Hardware Components

- ESP32 Development Board
- Soil Moisture Sensors
- DHT22 Sensor
- Relay Module
- Water Pump (Simulated)
- LCD1602 I2C Display
- OLED SSD1306 Display
- Buzzer
- Jumper Wires

⚙️ Working Principle

1. Soil moisture sensors continuously monitor soil conditions.
2. ESP32 analyzes the moisture level against predefined thresholds.
3. If the soil becomes dry, the relay activates the water pump automatically.
4. Once sufficient moisture is achieved, irrigation stops automatically.
5. LCD and OLED displays provide live sensor readings and pump status.
6. The system ensures efficient water usage while reducing manual intervention.

🔗 Wokwi Simulation

https://wokwi.com/projects/467186880132395009

---

🔐 Project 3 — Cloud Connected Security Node

📸 Project Preview

<p align="center">
<img src="IMAGES/security_node.jpg" width="750">
</p>📖 Overview

The Cloud Connected Security Node is an advanced IoT security system designed to provide intelligent intrusion detection, secure access control, and cloud-based monitoring. It integrates multiple sensors with ESP32 and the Blynk IoT platform to deliver real-time alerts, remote monitoring, and enhanced security for smart environments.

✨ Key Features

- 🚨 Intrusion Detection System
- ☁️ Blynk Cloud Integration
- 📡 Live IoT Telemetry
- 🔑 Keypad Authentication
- 🔒 Servo-Based Smart Lock
- 📏 Ultrasonic Distance Monitoring
- 👁 PIR Motion Detection
- 🌡 Temperature & Humidity Monitoring
- 📟 OLED Live Display
- 📺 LCD Status Display
- 🌈 RGB Security Indicators
- 🔔 Alarm & Buzzer Alerts

🛠️ Hardware Components

- ESP32 Development Board
- HC-SR04 Ultrasonic Sensor
- PIR Motion Sensor
- DHT22 Sensor
- 4×4 Matrix Keypad
- Servo Motor
- OLED SSD1306 Display
- LCD1602 I2C Display
- RGB LED
- Buzzer
- Blynk IoT Platform

⚙️ Working Principle

1. PIR and ultrasonic sensors continuously monitor the protected area.
2. ESP32 processes all sensor data in real time.
3. Unauthorized activity triggers visual and audible alerts.
4. The keypad authenticates users before unlocking the smart lock.
5. Servo motor controls the locking mechanism securely.
6. Live sensor data and security status are displayed on OLED, LCD, and the Blynk dashboard for remote monitoring.

🔗 Wokwi Simulation

https://wokwi.com/projects/467558183957384193

---

📊 Project Comparison

Project| Domain| Status
🌍 Smart Environment Monitoring| Environment| ✅ Completed
🌱 Automated Irrigation Controller| Smart Agriculture| ✅ Completed
🔐 Cloud Connected Security Node| Smart Security| ✅ Completed

---

🎯 Skills Demonstrated

- ESP32 Programming
- Embedded C++
- IoT System Development
- Sensor Interfacing
- Cloud Integration (Blynk)
- Real-Time Monitoring
- Smart Automation
- Hardware Simulation using Wokwi

---

📂 Repository Structure

DecodeLabs-Internship/
│
├── Smart-Environment-Monitor/
├── Automated-Irrigation-Controller/
├── Cloud-Connected-Security-Node/
├── IMAGES/
└── README.md

---

👨‍💻 Author

Vishal Mishra

🎓 DecodeLabs Internship

🔧 ESP32 & IoT Developer

📡 Embedded Systems Enthusiast

---

<div align="center">⭐ If you found these projects useful, consider giving this repository a Star!

Thank you for visiting my repository! 

</div>
