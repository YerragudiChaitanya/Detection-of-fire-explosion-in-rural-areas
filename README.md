# 🔥 Fire Detection and Alert System

This project is an Arduino-based fire detection and alert system using a **flame sensor**, **buzzer**, and **GSM module (SIM900)**. When a flame is detected, the system activates an alert by sounding a buzzer and making an automatic phone call to a predefined emergency number.

---

## 🚀 Features

- 🔍 Detects fire using a flame sensor  
- 🚨 Activates a buzzer as an alarm  
- 📞 Automatically calls a predefined phone number using a SIM900 GSM module  

---

## 🧰 Components Used

- Arduino Uno  
- Flame Sensor  
- SIM900 GSM Module  
- Buzzer  
- Connecting Wires  

---

## 🔌 Circuit Connections

### 🔥 Flame Sensor
- `VCC` → `5V`  
- `GND` → `GND`  
- `OUT` → `Digital Pin 2`  

### 🔔 Buzzer
- `Positive` → `Digital Pin 9`  
- `Negative` → `GND`  

### 📶 SIM900 GSM Module
- `TX` → `Digital Pin 11`  
- `RX` → `Digital Pin 10`  
- `VCC` → `5V`  
- `GND` → `GND`  

---

## ⚙️ Installation & Usage

1. Connect all components as per the circuit diagram.  
2. Insert a **SIM card** into the SIM900 module.  
3. Upload the `fire_alert.ino` sketch to the Arduino board.  
4. Open the **Serial Monitor** at **9600 baud rate** to view system logs.  
5. When fire is detected:
   - The **buzzer will sound**.
   - A **call will be placed** to the predefined emergency number.

---

## 📝 Notes

- Ensure your **SIM card** is activated and has **sufficient balance** to make calls.  
- The **flame sensor** may require **calibration** for optimal detection.  
- This system can be **expanded** to send SMS alerts or trigger other emergency responses.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 👤 Author

**Eluru Poojith Kumar**
