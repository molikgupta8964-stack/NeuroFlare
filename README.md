# 🔥 AI-Based IoT Fire Prediction System

An intelligent **fire prediction and alert system** built using **ESP32, MQ2 Gas Sensor, and Blynk IoT platform**.  
The system analyzes gas sensor data using an **AI-style predictive algorithm** to detect potential fire hazards and send **real-time alerts to a mobile device**.

---

## 🚀 Features

- 🔥 Real-time gas monitoring using MQ2 sensor
- 🤖 AI-style fire risk prediction algorithm
- 📟 16x2 I2C LCD display for local monitoring
- 🚨 Buzzer and LED alert system
- 📱 Mobile notifications via Blynk IoT platform
- 🎚 Adjustable risk threshold through Blynk slider
- 🌐 IoT connectivity using ESP32 WiFi

---

## 🧠 AI Prediction Logic

Instead of using a simple threshold-based detection system, this project calculates a **predictive fire risk score** using a weighted formula:

This allows the system to **predict fire hazards earlier** by analyzing trends in gas concentration.

---

## 🛠 Hardware Components

| Component | Quantity |
|----------|---------|
| ESP32 Development Board | 1 |
| MQ2 Gas Sensor | 1 |
| 16x2 LCD Display (I2C) | 1 |
| Buzzer | 1 |
| LED | 1 |
| Resistor (220Ω) | 1 |
| Breadboard | 1 |
| Jumper Wires | Multiple |

---

## 🔌 Hardware Connections

| Component | ESP32 Pin |
|----------|-----------|
| MQ2 Analog Output | 34 |
| LCD SDA | 21 |
| LCD SCL | 22 |
| Buzzer | 26 |
| LED | 27 |

---

## 📱 Blynk IoT Setup

1. Install the **Blynk IoT App**.
2. Create a **new project**.
3. Select **ESP32** as the device.
4. Add the following widgets:
   - Notification widget
   - Slider widget (Virtual Pin **V1**) for risk threshold.
5. Copy the **Auth Token** and paste it in the code.

---

## ⚙️ Installation & Setup

1. Install **Arduino IDE**.
2. Install the following libraries from the Library Manager:
