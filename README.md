# 🚀 DecodeLabs Internship Portfolio

<div align="center">

# 🌍 ESP32 IoT Projects Collection

### Smart Environment Monitoring • Smart Irrigation • Cloud Security • Smart Home Appliance Security

![ESP32](https://img.shields.io/badge/ESP32-IoT-red?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-C++-00979D?style=for-the-badge)
![Wokwi](https://img.shields.io/badge/Wokwi-Simulator-orange?style=for-the-badge)
![Blynk](https://img.shields.io/badge/Blynk-IoT-blue?style=for-the-badge)
![PlatformIO](https://img.shields.io/badge/PlatformIO-ESP32-orange?style=for-the-badge)

</div>

---

# 📖 About Repository

This repository contains four ESP32-based IoT projects developed during the DecodeLabs Internship. Each project demonstrates practical applications of embedded systems, cloud connectivity, sensors, automation, and real-time monitoring using the ESP32 microcontroller.

The projects were designed using Arduino C++, simulated in Wokwi, and integrated with the Blynk IoT Cloud wherever required.

---

# 📂 Repository Projects

| Project | Description |
|----------|-------------|
| 🌍 Smart Environment Monitoring System | Real-time monitoring of temperature, humidity, air quality, and environmental conditions. |
| 🌱 IoT-Based Smart Irrigation System | Automatic irrigation using soil moisture sensing and cloud monitoring. |
| 🔐 Cloud Connected Security Node | ESP32-based IoT security system with cloud monitoring and alert system. |
| 🏠 Smart Home Appliance Security System | Multi-sensor smart home security with OLED, LCD, Servo, Keypad and Blynk. |

---

# 🌍 Project 1 — Smart Environment Monitoring System

## 📷 Project Preview

> **Add your screenshot here**

```md
![Project Screenshot](images/project1.png)

---

📖 Overview

The Smart Environment Monitoring System continuously monitors environmental conditions using ESP32 and multiple sensors. It measures temperature, humidity, air quality, and displays real-time information on the OLED display. The project can also send cloud data through Blynk for remote monitoring.

---

✨ Key Features

- 🌡️ Real-Time Temperature Monitoring
- 💧 Humidity Detection
- 🌫️ Air Quality Monitoring
- 📟 OLED Live Display
- 🌈 RGB LED Status Indicator
- 🔔 Smart Alert System
- ☁️ Blynk Cloud Monitoring
- 📊 Live Sensor Data Visualization

---

🛠 Components Used

- ESP32 DevKit V1
- DHT11/DHT22 Sensor
- MQ2 Gas Sensor
- OLED Display
- RGB LED
- Buzzer
- Jumper Wires
- Breadboard

---

⚙️ Technologies Used

- ESP32
- Arduino C++
- Wokwi Simulator
- Blynk IoT
- Embedded Systems

---

🚀 Working Principle

1. ESP32 reads sensor values.
2. Temperature and humidity are measured using DHT11.
3. MQ2 detects harmful gases.
4. OLED displays live readings.
5. RGB LED indicates system status.
6. Buzzer alerts during abnormal conditions.
7. Sensor values are uploaded to Blynk Cloud.

---

📂 Project Files

- Source Code
- Circuit Diagram
- Wokwi Simulation
- README Documentation

---

🔗 Wokwi Simulation

«Paste your Wokwi Project Link here»

---

📸 Output

«Add project screenshot here.»

---
# 🌱 Project 2 — IoT-Based Smart Irrigation System

## 📷 Project Preview

> **Add your screenshot here**

```md
![Project Screenshot](images/project2.png)
```

---

## 📖 Overview

The IoT-Based Smart Irrigation System automates irrigation by continuously monitoring soil moisture levels using an ESP32 microcontroller. When the soil becomes dry, the system automatically activates the water pump and stops it when sufficient moisture is detected. The project also supports real-time monitoring through the Blynk IoT platform, reducing water wastage and improving irrigation efficiency.

---

## ✨ Key Features

- 🌱 Automatic Irrigation Control
- 💧 Soil Moisture Monitoring
- 🚰 Automatic Water Pump Control
- ☁️ Blynk Cloud Monitoring
- 📱 Remote Monitoring using Mobile
- 📟 OLED/LCD Status Display
- 🌈 RGB LED Status Indicator
- 🔔 Smart Alert Notifications
- ⚡ Low Power IoT Solution
- 🌍 Water Conservation System

---

## 🛠 Components Used

- ESP32 DevKit V1
- Soil Moisture Sensor
- Relay Module
- Water Pump (Simulated)
- OLED Display
- RGB LED
- Jumper Wires
- Breadboard

---

## ⚙️ Technologies Used

- ESP32
- Arduino C++
- Wokwi Simulator
- Blynk IoT
- Embedded Systems

---

## 🚀 Working Principle

1. ESP32 continuously reads the soil moisture sensor.
2. If soil moisture falls below the threshold, the relay turns ON.
3. The relay activates the water pump.
4. Once adequate moisture is reached, the pump automatically turns OFF.
5. Live system status is displayed on the OLED/LCD.
6. Sensor values are sent to the Blynk Cloud.
7. Users can monitor irrigation remotely using the Blynk mobile app.

---

## 📂 Project Files

- Source Code
- Circuit Diagram
- Wokwi Simulation
- README Documentation

---

## 🔗 Wokwi Simulation

> Paste your Wokwi Project Link here.

---

## 📸 Output

> Add project screenshot here.

---
# 🔐 Project 3 — Cloud Connected Security Node

## 📷 Project Preview

> **Add your screenshot here**

```md
![Project Screenshot](images/project3.png)
```

---

## 📖 Overview

The Cloud Connected Security Node is an ESP32-based IoT security system designed to monitor environmental conditions and improve home safety through cloud connectivity. It continuously monitors temperature, humidity, gas leakage, and ambient light while displaying live information on OLED and LCD displays. Using the Blynk IoT platform, users can remotely monitor the system and receive instant alerts whenever abnormal conditions are detected.

---

## ✨ Key Features

- ☁️ Cloud Monitoring using Blynk
- 🌡️ Temperature Monitoring
- 💧 Humidity Monitoring
- 🔥 MQ2 Gas Leak Detection
- 💡 Automatic Light Detection (LDR)
- 📟 OLED Live Sensor Display
- 🖥️ LCD Status Display
- 🌈 RGB LED Status Indicator
- 🔔 Smart Buzzer Alarm
- 📱 Remote Monitoring from Mobile
- ⚡ Real-Time Sensor Updates

---

## 🛠 Components Used

- ESP32 DevKit V1
- DHT11 Sensor
- MQ2 Gas Sensor
- LDR Sensor
- OLED Display
- 16x2 LCD Display (I2C)
- RGB LED
- Active Buzzer
- Blynk IoT Platform
- Breadboard
- Jumper Wires

---

## ⚙️ Technologies Used

- ESP32
- Arduino C++
- Wokwi Simulator
- Blynk IoT
- Embedded Systems
- IoT Cloud

---

## 🚀 Working Principle

1. ESP32 continuously reads all connected sensors.
2. DHT11 measures temperature and humidity.
3. MQ2 detects gas leakage.
4. LDR measures surrounding light intensity.
5. OLED and LCD display live sensor values.
6. RGB LED indicates SAFE or WARNING status.
7. Buzzer activates during abnormal conditions.
8. All sensor data is uploaded to the Blynk Cloud.
9. Users can monitor the system remotely through the Blynk mobile application.

---

## 📂 Project Files

- Source Code
- Circuit Diagram
- Wokwi Simulation
- README Documentation

---

## 🔗 Wokwi Simulation

> Paste your Wokwi project link here.

---

## 📸 Output

> Add project screenshot here.

---
# 🏠 Project 4 — Smart Home Appliance Security System

## 📷 Project Preview

> **Add your screenshot here**

```md
![Project Screenshot](images/project4.png)
```

---

## 📖 Overview

The Smart Home Appliance Security System is an ESP32-based IoT project developed to improve home security and automation. It integrates multiple sensors and smart devices to monitor environmental conditions, detect gas leakage, control door access through password authentication, and provide real-time cloud monitoring using the Blynk IoT platform. The system displays live information on both OLED and LCD displays while providing visual and audible alerts during emergency situations.

---

## ✨ Key Features

- 🔐 Password Protected Smart Door Lock
- ☁️ Blynk Cloud Monitoring
- 🔥 MQ2 Gas Leak Detection
- 🌡️ Temperature & Humidity Monitoring
- 💡 Automatic LDR Light Detection
- 🔢 4×4 Keypad Authentication
- ⚙️ Servo Motor Door Control
- 📟 OLED Live Sensor Display
- 🖥️ LCD Status Display
- 🌈 RGB LED Status Indicator
- 🚨 Smart Buzzer Alarm
- 📱 Real-Time IoT Monitoring
- ⚡ Intelligent Home Automation

---

## 🛠 Components Used

- ESP32 DevKit V1
- DHT11 Sensor
- MQ2 Gas Sensor
- LDR Sensor
- OLED Display (SSD1306)
- 16×2 LCD Display (I2C)
- 4×4 Matrix Keypad
- Servo Motor
- RGB LED
- Active Buzzer
- Blynk IoT Platform
- Breadboard
- Jumper Wires

---

## ⚙️ Technologies Used

- ESP32
- Arduino C++
- PlatformIO
- Wokwi Simulator
- Blynk IoT
- Embedded Systems
- IoT Cloud

---

## 🚀 Working Principle

1. The user enters a password using the keypad.
2. If the password is correct, the servo motor unlocks the door.
3. DHT11 continuously monitors temperature and humidity.
4. MQ2 detects gas leakage in real time.
5. LDR monitors ambient light intensity.
6. OLED and LCD display live sensor readings.
7. RGB LED indicates the current system status.
8. The buzzer activates whenever dangerous conditions are detected.
9. Sensor values are uploaded to the Blynk Cloud for remote monitoring.
10. Users can monitor the complete system from the Blynk mobile application.

---

## 📂 Project Files

- Source Code
- Circuit Diagram
- Wokwi Simulation
- README Documentation

---

## 🔗 Wokwi Simulation

> Paste your Wokwi Project Link here.

---

## 📸 Output

> Add your project screenshots here.

```md
![Screenshot 1](images/project4.png)

![Screenshot 2](images/project4_output.png)
```

---

## 🎯 Project Outcome

This project demonstrates a complete cloud-connected smart home security solution capable of protecting home appliances and providing real-time monitoring through IoT technology. It combines embedded systems, cloud computing, automation, and sensor integration into a single intelligent security platform.

---
# 📁 Repository Structure

```text
DecodeLabs-Internship
│
├── README.md
│
├── Project-1-Smart-Environment-Monitoring
│   ├── src
│   ├── platformio.ini
│   ├── diagram.json
│   └── images
│
├── Project-2-Smart-Irrigation-System
│   ├── src
│   ├── platformio.ini
│   ├── diagram.json
│   └── images
│
├── Project-3-Cloud-Connected-Security-Node
│   ├── src
│   ├── platformio.ini
│   ├── diagram.json
│   └── images
│
└── Project-4-Smart-Home-Appliance-Security-System
    ├── src
    ├── platformio.ini
    ├── diagram.json
    ├── wokwi.toml
    └── images
```

---

# 💻 Software & Tools Used

- ESP32 DevKit V1
- Arduino C++
- PlatformIO
- Wokwi Simulator
- Blynk IoT
- GitHub
- VS Code

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/DecodeLabs-Internship.git
```

## Open Project

Open the required project folder using **VS Code + PlatformIO**.

## Install Libraries

Install all required dependencies from the `platformio.ini` file.

## Build Project

Click the **Build (✓)** button in PlatformIO.

## Run Simulation

Open the project in **Wokwi Simulator** and start the simulation.

---

# 📸 Project Gallery

Add screenshots of all projects here.

## 🌍 Smart Environment Monitoring

```md
![Environment](images/project1.png)
```

## 🌱 Smart Irrigation

```md
![Irrigation](images/project2.png)
```

## 🔐 Cloud Connected Security Node

```md
![Security Node](images/project3.png)
```

## 🏠 Smart Home Appliance Security

```md
![Smart Home](images/project4.png)
```

---

# 🔮 Future Improvements

- AI-Based Threat Detection
- Voice Command Integration
- Mobile Push Notifications
- Smart Energy Monitoring
- Face Recognition Door Lock
- Fingerprint Authentication
- Cloud Data Analytics
- Google Assistant Integration
- Alexa Integration
- OTA Firmware Updates

---

# 🎓 Internship

Developed as part of the **DecodeLabs Internship Program**.

---

# 👩‍💻 Author

**Dipti Kumari**

- Embedded Systems Enthusiast
- IoT Developer
- ESP32 & Arduino Programmer

---

# ⭐ Support

If you found these projects useful:

⭐ Star this repository

🍴 Fork the repository

📢 Share it with others

---

# 📜 License

This repository is created for educational purposes under the DecodeLabs Internship Program.
