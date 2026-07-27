# 💡 Move to Glow
### Motion Detection Based Automatic Lighting System using Arduino UNO
---

## 📖 Project Overview

**Move to Glow** is a smart automation project that automatically turns a light **ON** when motion is detected and turns it **OFF** when no motion is present. The system uses a **PIR Motion Sensor** to detect human movement and an **Arduino Uno** to control the lighting. A **16×2 I2C LCD** provides real-time system status, making the project suitable for smart homes, offices, corridors, and energy-saving applications.

---

## 🚀 Features

- 👤 Detects human motion using a PIR sensor
- 💡 Automatically switches the light ON/OFF
- 📟 Displays motion status on a 16×2 I2C LCD
- 🔋 Helps reduce unnecessary power consumption
- 🛠️ Simple and beginner-friendly Arduino project
- 🧪 Fully simulated in Tinkercad

---

## 🛠️ Components Used

| Component | Quantity |
|---|---|
| Arduino Uno R3 | 1 |
| PIR Motion Sensor | 1 |
| 16×2 I2C LCD Display | 1 |
| Light Bulb (Output) | 1 |
| 1kΩ Resistor | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |

---

## ⚙️ Working Principle

1. The system initializes and waits for motion.
2. The PIR sensor continuously monitors the surrounding area.
3. **When motion is detected:**
   - The Arduino receives a `HIGH` signal.
   - The light turns **ON**.
   - LCD displays:
     ```
     Motion DET: YES
     Light ST: ON
     ```
4. **When no motion is detected:**
   - The light turns **OFF**.
   - LCD displays:
     ```
     Motion DET: NO
     Light ST: OFF
     ```
5. The current status is also printed on the **Serial Monitor** for debugging.

---

## 🔌 Circuit Connections

### PIR Sensor

| PIR Pin | Arduino |
|---|---|
| VCC | 5V |
| GND | GND |
| OUT | D2 |

### I2C LCD

| LCD Pin | Arduino |
|---|---|
| VCC | 5V |
| GND | GND |
| SDA | A4 |
| SCL | A5 |

### Light

| Component | Arduino |
|---|---|
| Light Bulb | Digital Output Pin |

---

## 💻 Software Used

- Arduino IDE
- Tinkercad Circuits
- C/C++ (Arduino Programming)
  
---

## ▶️ How to Run

1. Open the project in **Tinkercad Circuits** or wire the physical circuit as per the connections above.
2. Open `MoveToGlow.ino` in the **Arduino IDE**.
3. Install the **LiquidCrystal_I2C** library (via Library Manager) if not already installed.
4. Select **Arduino Uno** as the board and the correct COM port.
5. Upload the sketch.
6. Open the **Serial Monitor** (9600 baud) to view live motion/light status logs.

---

## 📈 Applications

- Smart Home Automation
- Automatic Corridor Lighting
- Office Lighting
- Security Systems
- Energy Conservation
- Motion-Activated Indoor Lighting

---

## 🎯 Future Enhancements

- 📡 Wi-Fi based remote monitoring (ESP8266/ESP32)
- ☁️ IoT Dashboard integration
- 📱 Mobile App Control
- ⏱️ Adjustable Light Timeout
- 🌗 LDR-based Day/Night Detection
- 📩 Email/SMS Alerts
- 📊 Energy Usage Analytics

---

## 👨‍💻 Author

**Mallampally Jayantha Siva Srinivas** |
Electronics and Communication Engineering (ECE)
---
