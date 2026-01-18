# ESP32 Smart Camera

## 🎯 Project Purpose
This project was developed to demonstrate motion detection, real-time image capture, and IoT-based notification systems using low-cost hardware.

## 🚀 Features
- 📷 Real-time photo capture with ESP32-CAM
- 👀 Motion detection using a PIR sensor
- 🤖 Telegram bot integration for instant notifications
- 🔔 Alarm activation upon motion detection
- 🌐 Remote alerts over Wi-Fi

## 🧠 System Overview
The system continuously monitors motion using a PIR sensor. When motion is detected, ESP32-CAM captures an image and sends it to the user via a Telegram bot over Wi-Fi while triggering an audible alarm.

## 🛠️ Hardware Components
- ESP32-CAM
- PIR Motion Sensor
- Buzzer (Alarm)
- Jumper wires
- 5V power supply

## 🧩 Technologies Used
- Arduino Framework
- Telegram Bot API
- Wi-Fi Communication

## 🔌 Connections
- PIR OUT → ESP32 GPIO (e.g., GPIO 13)
- Buzzer → ESP32 GPIO
- ESP32-CAM → 5V / GND

## ⚙️ How It Works
1. The PIR sensor detects motion in the environment.
2. ESP32-CAM is triggered and captures a photo.
3. The captured image is sent to the user via a Telegram bot.
4. An audible alarm is activated using the buzzer.

## 📸 Project Images
![image alt](https://github.com/AliHuseyn19/esp32-smart-camera/blob/46831b1968e7d843c5944b042e71056c9c587add/Devre_Semasi.jpg)

## 🎯 Use Cases
- Home security
- Office monitoring
- Warehouse and entrance control
- IoT-based security projects
