# 🌤️ Climate Station – Arduino Project
A simple climate monitoring station using **DHT11 sensor** and an **SSD1306 128x64 OLED display**.  
The system reads **temperature** and **humidity**, then displays them on the OLED with custom icons and text graphics.

---

## 📌 Features
- Reads **Temperature (°C)** using DHT11  
- Reads **Humidity (%)** using DHT11  
- Displays data on **128×64 OLED SSD1306**  
- Custom icons for weather, sun, temperature, wind, etc.  
- Smooth refreshing and clean UI

---

## 🛠️ Hardware Requirements
- Arduino (Uno/Nano/Mega…)  
- DHT11 Sensor  
- SSD1306 OLED Display (I2C – 128×64)  
- Jumper wires  
- Breadboard  

---

## 🔌 Circuit Connections

### **DHT11 → Arduino**
| DHT11 Pin | Arduino Pin |
|----------|-------------|
| VCC      | 5V          |
| GND      | GND         |
| DATA     | D10         |

### **OLED SSD1306 → Arduino**
| OLED Pin | Arduino Pin |
|----------|-------------|
| GND      | GND         |
| VCC      | 5V          |
| SDA      | A4 (SDA)    |
| SCL      | A5 (SCL)    |

---

## 📦 Libraries Used

Make sure to install the following libraries:
DHT.h
DHT_U.h
Adafruit_SSD1306
Adafruit GFX Library
