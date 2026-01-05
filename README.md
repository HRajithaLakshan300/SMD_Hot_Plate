# 🔥 ESP32 Web-Controlled SMD Hot Plate

A smart **SMD reflow hot plate** controlled through a **web interface** hosted on **GitHub Pages**, using **MQTT communication** and an **ESP32** microcontroller.

This hot plate allows **smooth temperature control** for:
- SMD component **assembly (reflow soldering)**
- SMD component **disassembly (desoldering)**

---

## 🚀 Features

- 🌐 Web-based temperature control (GitHub-hosted UI)
- 📡 MQTT-based communication between website and ESP32
- 🎛 Smooth and stable temperature control
- 🔥 SSR-based heater switching
- 🌡 Thermocouple temperature feedback
- 🧯 Safety fuse and power switch
- 🖥 LED temperature display
- ⚡ Designed for PCB SMD reflow and repair work

---

## 🧠 System Overview

The system consists of:
- A **web interface** to set and monitor temperature
- An **MQTT broker** to transmit commands
- An **ESP32** that controls heating via an **SSR**
- A **thermocouple** for real-time temperature feedback

---

## 🧩 Hardware Components

- ESP32 microcontroller  
- Solid State Relay (SSR)  
- Thermocouple (with amplifier module)  
- Heating plate  
- Fuse (for overcurrent protection)  
- Power switch (connected in series with fuse and SSR)  
- LED temperature display  
- Power supply  

---

## 🔌 Hardware Connection Summary

- Thermocouple → ESP32 (temperature sensing)
- ESP32 → SSR → Heater
- Fuse + Switch → SSR input power line
- LED Display → ESP32 (temperature display)

---

## 🌐 Web Interface

- Hosted using **GitHub Pages**
- Allows:
  - Temperature setpoint control
  - Real-time temperature monitoring
- Communicates with ESP32 via **MQTT broker**

---

## 📡 Communication

- Protocol: **MQTT**
- ESP32 subscribes to temperature control topics
- Web interface publishes temperature setpoints

---

## 🛡 Safety Features

- Fuse protection against overcurrent
- Manual power switch
- Controlled temperature ramping to avoid PCB damage

---

## 🎯 Project Goal

The main goal of this project is to:
- Provide an **affordable and precise SMD reflow solution**
- Enable **smooth assembly and disassembly of SMD components**
- Combine **IoT + electronics manufacturing tools**

---

## 🛠 Future Improvements

- Reflow temperature profiles (preheat, soak, reflow, cooldown)
- PID temperature control
- Data logging and temperature graphs
- Mobile-friendly UI
- Emergency thermal cutoff

---

## 👤 Author

**Rajitha Lakshan**  
- LinkedIn: *(add your LinkedIn link here)*  
- GitHub: *(your GitHub profile link)*  

---

## 📜 License

This project is open-source and available under the MIT License.
