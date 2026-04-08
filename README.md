# 🌱 Environmental Monitoring System (KiCad)

## 📌 Description

This project is a **PCB-based environmental monitoring system** designed using KiCad. It uses an ESP32 microcontroller to monitor **temperature, humidity, and gas levels** in real time.

Unlike basic designs, this system includes a **custom-built analog signal processing stage using LM393 comparator**, instead of relying on prebuilt sensor modules.

---

## 📷 Project Preview

![PCB Design](pcb_env_system_final.jpg)

---

## ⚙️ Key Design Highlight

🔹 **Custom Comparator Circuit (LM393)**

* Designed a **gas detection comparator circuit** using LM393
* Converts analog signal from MQ sensor into digital output
* Adjustable threshold using potentiometer
* Improves flexibility and understanding of analog design

---

## ⚙️ Components Used

* ESP32 Development Board
* DHT11 Sensor (Temperature & Humidity)
* MQ-6 Gas Sensor
* LM393 Comparator IC
* LCD Display (16x2 - WC1602A)
* Potentiometers (for threshold tuning)
* Resistors & Capacitors
* LED Indicator
* Power Supply Circuit

---

## 🔧 Features

* Real-time temperature and humidity monitoring
* Gas detection with adjustable sensitivity
* Custom analog comparator design (LM393)
* LCD-based output display
* Compact PCB layout

---

## 📁 Bill of Materials (BOM)

| Component             | Quantity | Description            |
| --------------------- | -------- | ---------------------- |
| ESP32 DevKit V1       | 1        | Main controller        |
| DHT11                 | 1        | Temp & humidity sensor |
| MQ-6                  | 1        | Gas sensor             |
| LM393                 | 1        | Comparator IC          |
| WC1602A LCD           | 1        | Display                |
| Resistors (2.2k, 10k) | Multiple | Biasing                |
| Capacitors (100nF)    | 2        | Filtering              |
| Potentiometers        | 2        | Threshold control      |
| LED                   | 1        | Indicator              |

---

## 🛠️ Tools Used

* KiCad (Schematic & PCB Design)
* Arduino IDE (ESP32 Programming)

---

## 🚀 Applications

* Air Quality Monitoring
* Gas Leakage Detection
* Smart Home Systems
* Industrial Safety Monitoring

---

## 🔮 Future Improvements

* IoT Cloud Integration
* Mobile App Monitoring
* Data Logging System
* Multi-sensor expansion

---

## 👨‍💻 Author

**Md Ayan Akhtar Khan**
B.Tech (ECE)
