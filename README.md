# 🔌 IoT Based Smart Energy Meter

This project presents the design and implementation of an **IoT-enabled Smart Energy Meter** using **Arduino Mega 2560** and **GSM module** for remote energy monitoring, real-time data transmission, and automated billing.

> 📍 Developed as part of the final year B.Tech (Electrical Engineering) project at **Sardar Patel College of Engineering**, Mumbai.

---

## 📖 Project Overview

With rising energy demands and distribution losses, utility companies need modern metering systems that are efficient, accurate, and remotely manageable. This project aims to:

- Automate electricity usage monitoring.
- Provide real-time power factor and energy readings.
- Enable remote disconnection/reconnection of power supply via SMS.
- Replace manual meter reading with GSM-based automatic meter reporting.

---

## ⚙️ Technologies & Components

- **Microcontroller:** Arduino Mega 2560
- **Sensors:**
  - SCT-013 Current Transformer
  - Voltage Divider Circuit with Step-down Transformer
- **Communication:** GSM SIM900A module
- **Display & Monitoring:**
  - Real-time readings via Serial Monitor
  - SMS alerts for remote monitoring
- **Additional Hardware:** Solid State Relay, Bridge Rectifier, Smoothing Capacitor

---

## 🧮 Features

- RMS Voltage and Current Measurement
- Real and Apparent Power Calculation
- Power Factor Calculation
- GSM-based Remote Control (SMS-based ON/OFF)
- Energy Theft Detection Possibility (Future Scope)
- Arduino-compatible sensor interface

---

## 🧰 Installation & Setup

### Hardware
1. Assemble the circuit with current and voltage sensors connected to Arduino Mega.
2. Connect SIM900A GSM module with RS232 to the Arduino.
3. Power up using a 12V DC adapter.

### Software
1. Upload the Arduino sketch from `energy_meter.ino`.
2. Open the serial monitor at 9600 baud rate to view real-time readings.
3. Send SMS commands to control the relay and monitor the energy data remotely.

---

📌 Applications

- Smart billing and tariff planning
- Real-time energy monitoring
- Remote energy control for distributed assets
- Load profiling and usage analytics

🔮 Future Scope
- Integration with home automation systems
- Real-time theft detection with pattern recognition
- Two-way power flow monitoring (for renewable integration)
- Prepaid metering functionality
