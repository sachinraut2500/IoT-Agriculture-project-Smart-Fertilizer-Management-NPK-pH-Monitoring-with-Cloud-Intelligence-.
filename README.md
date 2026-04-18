# 🌱 Smart Fertilizer Management (IoT + Cloud Intelligence)
--------------------------
## 📖 Overview
This project monitors **soil nutrients (NPK), pH, and EC (salinity)** using IoT sensors.  
The ESP32 node collects data and sends it to the **cloud via MQTT**.  
The Raspberry Pi gateway processes data and gives **fertilizer recommendations**.
------------------

## ⚙️ Features
- Soil **NPK** sensor for nutrients  
- **pH** sensor for acidity/alkalinity  
- **EC** sensor for soil salinity  
- IoT data transfer via **MQTT**  
- **Rule-based decision system** for fertilizer recommendations  
- Can be extended with **Machine Learning**  

---------------

## 🛠 Hardware
- ESP32 (MicroPython)  
- NPK sensor (UART/I2C)  
- pH sensor  
- EC sensor  
- Raspberry Pi (cloud gateway)  

-------------

## 🧑‍💻 Software
- MicroPython on ESP32  
- Python 3 on Raspberry Pi  
- Dependencies:
```bash
pip install paho-mqtt
