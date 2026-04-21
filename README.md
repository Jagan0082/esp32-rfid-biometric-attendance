# ESP32 Biometric & RFID Attendance System

## 📌 Overview

A complete embedded attendance system built on ESP32 with RFID and biometric integration. Designed for real-time logging, reliability, and industrial use cases.

## ⚙️ Key Features

* RFID + Fingerprint authentication
* FreeRTOS-based concurrent task handling
* HTTP web dashboard (Add/Edit/Delete users)
* NTP-based time synchronization
* Offline data storage (NVS)
* LCD/TFT real-time feedback

## 🧠 System Architecture

* ESP32 (ESP-IDF)
* SPI (RC522 RFID)
* I2C (Display)
* UART (Fingerprint sensor)
* LwIP TCP/IP stack

## 🔧 Core Concepts Implemented

* ISR-based event handling
* Driver-level SPI & I2C communication
* FreeRTOS tasks, queues, semaphores
* Embedded web server (HTTP + JSON)

## 🚀 Getting Started

1. Clone repository
2. Configure Wi-Fi credentials
3. Build using Aurdino IDE
4. Flash to ESP32

## 📷 Preview
<img width="1080" height="1600" alt="image" src="https://github.com/user-attachments/assets/a23f48f5-9ac2-4528-94c4-82a84d4389cf" />
<img width="1025" height="1280" alt="image" src="https://github.com/user-attachments/assets/176a1c71-4284-4dab-b204-c81171293a6e" />
<img width="935" height="1280" alt="image" src="https://github.com/user-attachments/assets/b068d053-389f-4699-bd13-efcb43f47a1f" />


## 📈 Future Improvements

* Cloud sync (MQTT / Firebase)
* Mobile app integration
