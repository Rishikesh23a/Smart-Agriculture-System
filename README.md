# Smart-Agriculture-System
IoT-based Smart Agriculture System using ESP8266, DHT11, Soil Moisture Sensor, and pH Sensor integrated with Firebase and realtime displays on MIT app Inventor 

## 📖 Project Overview
This project is an **IoT-based Smart Agriculture System** that monitors key environmental parameters like **temperature, humidity, soil moisture, and pH levels** using the **ESP8266 NodeMCU** microcontroller.  
The collected data is uploaded to **Firebase Realtime Database**, allowing remote monitoring through a **mobile app** built using **MIT App Inventor**.

This system helps farmers or researchers observe field conditions in real time, promoting **data-driven agriculture** and **optimized irrigation**.

---

## 🔧 Features
- 🌡️ Real-time temperature and humidity monitoring using DHT11  
- 💧 Soil moisture and pH data collection for crop health analysis  
- ☁️ Firebase Realtime Database integration  
- 📱 MIT App Inventor-based mobile dashboard  
- 🔄 Continuous data upload and refresh every few seconds  
- 🧠 Low-cost and scalable IoT design

---

## 🧰 Components Used
| Component | Description |
|------------|--------------|
| ESP8266 NodeMCU | Main controller board with built-in WiFi |
| DHT11 Sensor | Measures temperature and humidity |
| Soil Moisture Sensor | Detects soil water content |
| pH Sensor | Measures acidity/alkalinity of soil |
| Jumper Wires & Breadboard | For connections |
| Firebase | Cloud platform for data storage |
| MIT App Inventor | For building mobile app |

---
## 🧠 Working Principle
1. Sensors (DHT11, Moisture, and pH) collect live environmental data.  
2. The ESP8266 reads sensor data and connects to Wi-Fi.  
3. Using the Firebase API key and URL, it uploads data to the cloud.  
4. The Firebase Realtime Database stores and updates values continuously.  
5. The MIT App Inventor app fetches and displays the latest readings to the user.

---
## 🧩 Firebase Setup Summary
1. Create a new project on [Firebase Console](https://console.firebase.google.com/).  
2. Go to **Realtime Database → Create Database → Test Mode**.  
3. Copy the **Database URL** (e.g., `https://smartfarm-default-rtdb.firebaseio.com/`).  
4. Get your **API Key** from **Project Settings → General → Web API Key**.  
5. Replace both values in the `.ino` code.  
6. Upload code to ESP8266 and monitor live data.

---

## 📱 Mobile App (MIT App Inventor)
- Simple UI showing:
  - Temperature
  - Humidity
  - Moisture Level
  - pH Value
- Fetches live Firebase readings
- Provides alerts for extreme values  

---

`````
## 🧩 Folder Structure
Smart-Agriculture-System/
│
├─ code/
│ ├─ smart_agriculture.text # Arduino code for ESP8266
│ ├─ libraries-list.txt # List of libraries used
│
├─ app/
│ ├─ app_blocks.png
│ ├─ app_home.png
│
├─ docs/
│ ├─ serial_monitor.png
│ ├─ wiring_diagram_pic.png
│ ├─ Realime_database_firebase.png
│ ├─ firebase_setup.text
│
├─ data/
│ ├─ sample_readings.csv

`````

## 🧾 Learning Outcomes
- Gained hands-on experience with **GitHub issue tracking and collaboration**  
- Understood **IoT data flow** from sensors → microcontroller → cloud → app  
- Learned to document and resolve software/hardware QA issues  
- Understood how to manage and organize embedded projects on GitHub  
- Improved teamwork and communication through version control

## 🚀 Future Improvements
- Add automatic irrigation control using relay and pump  
- Integrate weather API for external data comparison  
- Implement AI-based crop suggestion or anomaly detection  
- Use solar power for sustainable operation

## 👨‍💻 Contributors
Rushikesh Sable 

MIT AOE Collage

rushikeshsable9850@gmail.com
