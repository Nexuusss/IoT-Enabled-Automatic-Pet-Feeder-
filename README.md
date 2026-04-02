# 🐾 IoT-Enabled Automatic Pet Feeder  
### With Environmental Control using ESP32 & Blynk

---

## 📌 Overview  
This project presents a smart IoT-based pet feeding system designed to automate feeding while enabling real-time monitoring and remote control. The system uses an ESP32 microcontroller integrated with sensors and actuators to ensure pets are fed on time, even when the owner is away.

It supports both **automatic scheduled feeding** and **manual control using smartphone**, making it flexible and reliable.

---

## 🚀 Features  
- ⏰ Scheduled automatic feeding  
- 📱 Remote control using Blynk mobile app  
- 📡 Real-time food level monitoring  
- 🐕 Motion-based feeding using PIR sensors  
- 🔔 Alerts using buzzer and LED  
- 🌬️ Environmental control (ventilation system)  
- 📟 LCD display for live system status  
- 🌐 WiFi-enabled IoT connectivity  

---

## 🛠️ Hardware Components  
- ESP32 Microcontroller  
- Servo Motor (food dispensing)  
- Ultrasonic Sensor (food level detection)  
- PIR Sensors (motion detection)  
- DC Motor (ventilation system)  
- Buzzer & LED (alerts)  
- 16x2 I2C LCD Display  
- Breadboard & Connecting Wires  
- 5V Power Supply  

---

## 💻 Software & Tools  
- Arduino IDE  
- Blynk IoT Platform  
- ESP32 Board Package  

### 📚 Required Libraries  
- WiFi.h  
- BlynkSimpleEsp32.h  
- ESP32Servo.h  
- NewPing.h  
- LiquidCrystal_I2C.h  
- TimeLib.h  
- Wire.h  

---

## ⚙️ System Architecture  

The system consists of four main layers:

### 1. Input Layer  
- Ultrasonic sensor measures food level  
- PIR sensors detect pet movement  

### 2. Processing Layer  
- ESP32 processes data and controls logic  

### 3. Output Layer  
- Servo motor dispenses food  
- LCD, buzzer, LED provide feedback  

### 4. IoT Layer  
- Blynk app enables remote monitoring and control  

---

## 🔄 Working Procedure  
1. System initializes and connects to WiFi & Blynk  
2. Checks feeding schedule continuously  
3. Dispenses food automatically at set times  
4. Allows manual feeding via mobile app  
5. Monitors food level every few seconds  
6. Detects pet motion and triggers feeding if needed  
7. Updates all data in real time on LCD and Blynk  

---

## 📊 Performance Highlights  
- Accurate feeding without delay  
- Food level detection accuracy ≈ ±1 cm  
- Real-time data updates within 1–2 seconds  
- Reliable motion detection within 120° range  

---

## ⚠️ Limitations  
- Requires stable internet connection  
- No backup power system  
- Fixed food portion size  
- No live video monitoring  

---

## 🔮 Future Improvements  
- 🔋 Battery backup system  
- 📷 Camera integration for live monitoring  
- ⚖️ Load cell for precise food measurement  
- 🤖 AI-based smart feeding prediction  

---

## 📌 Conclusion  
This project demonstrates how IoT can be applied to automate daily tasks like pet feeding while ensuring reliability, flexibility, and real-time monitoring. It is scalable and can be enhanced with advanced technologies like AI and computer vision.
