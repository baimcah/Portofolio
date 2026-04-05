# Mini Automatic Clothes Drying System

## 📌 Project Overview

Developed a smart clothes drying system with automatic weather detection and response. 
System monitors weather conditions and automatically retracts/deploys based on rain or sunshine.

**Status:** Completed & Functional
**Duration:** 1 month
**Platform:** ESP32 + Arduino

---

## 🎯 Problem Solved

- ❌ Manual clothesline management → tedious & weather-dependent
- ❌ Risk of wet clothes due to unexpected rain
- ❌ Need constant monitoring during drying
- ❌ Time-consuming manual retraction/deployment

---

## ✅ Solution Implemented

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Light Sensor** | LDR (photoresistor) | Detect cloud cover |
| **Rain Sensor** | Capacitive/resistive sensor | Detect rain drops |
| **Motor Control** | Servo motor + ESP32 | Automatic retraction mechanism |
| **Logic** | Arduino/ESP32 | Decision making & automation |
| **Power** | Battery/solar | Self-sustaining operation |

---

## 📊 Results

- 🌧️ **Auto-retract** in <5 seconds when rain detected
- ☀️ **Auto-deploy** when weather clears
- ⏱️ **Zero manual intervention** required
- 🔋 **Low power consumption** with intelligent logic
- 💪 **Servo-driven** mechanism for reliable operation

---

## 🔧 How It Works

1. **Sensor Reading** → Light & rain sensors continuously monitor
2. **Logic Decision** → Microcontroller evaluates conditions
3. **Threshold Check** → If rain detected OR darkness increasing
4. **Motor Activation** → Servo motor retracts clothesline
5. **Safety Stop** → Motor stops at end-of-travel
6. **Monitoring** → Waits for clear weather to redeploy

---

## 🛠️ Tech Stack

- **Microcontroller:** ESP32 or Arduino
- **Sensors:** LDR (light), capacitive rain sensor
- **Motor:** Servo motor SG90 (or similar)
- **Power:** Battery (18650) or solar panel
- **Programming:** Arduino IDE (C/C++)

---

## 🚀 Key Learnings

- Sensor integration (light, rain detection)
- Servo motor control & timing
- Decision logic for automation
- Power management for battery operation
- Consumer IoT design

---

## 📞 Contact

Email: mibrahimsyah5@gmail.com
