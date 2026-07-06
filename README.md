# 🚗 EV ADAS Dashboard

A real-time **Electric Vehicle Advanced Driver Assistance System (ADAS) Dashboard** developed using **STM32 Blue Pill (STM32F103C8T6)**, **PicsimLab**, and **Python**. This project simulates an EV dashboard capable of monitoring vehicle parameters and displaying ADAS information through a live Python dashboard.

---

## 📌 Project Overview

The EV ADAS Dashboard is designed to monitor and visualize important electric vehicle parameters in real time. Sensor values are processed by the STM32 microcontroller, transmitted through UART, and displayed on a Python-based dashboard.

The project demonstrates the integration of embedded systems, serial communication, and data visualization.

---

## ✨ Features

- 🚗 Real-time Vehicle Speed Monitoring
- 🔋 Battery State of Charge (SOC)
- 🌡️ Motor Temperature Monitoring
- ⚡ Torque Calculation
- 📏 Estimated Driving Range
- 🚨 Forward Collision Warning (FCW)
- 👀 Blind Spot Detection (BSD)
- ⚠️ Fault Detection & Alarm System
- 🔄 Multiple Drive Modes (ECO / NORMAL / SPORT)
- 📡 UART Communication
- 📊 Live Python Dashboard

---

## 🛠 Hardware Used

- STM32 Blue Pill (STM32F103C8T6)
- HC-SR04 Ultrasonic Sensor
- Potentiometers
- LEDs
---

## 💻 Software Used

- STM32CubeIDE
- STM32CubeMX
- PicsimLab
- Python 3
- Matplotlib
- PySerial

---

## 📂 Repository Structure

```text
EV_ADAS_Dashboard
│
├── Firmware
│   ├── ADC
│   ├── EV_Dash
│   ├── Timer1_1Sec
│   └── Ultrasonic_Sensor
│
├── Python_Dashboard
│
├── Presentation
│
├── Images
│
├── README.md
├── LICENSE

```

---

## 📷 Project Screenshots

### Python Dashboard



Images/Python_Dashboard_Output_ADVISORY Alarm.png

---

## ▶️ How to Run

1. Open the firmware project using STM32CubeIDE.
2. Build the firmware.
3. Run the project using PicsimLab or STM32 hardware.
4. Connect the UART serial port.
5. Run the Python dashboard.
6. Observe the live EV dashboard.

---

## 👩‍💻 Author

**Indhira A**

Electronics Engineering Student

Interested in:
- Embedded Systems
- PCB Design
- STM32 Development
- Automotive Electronics
- EV Technologies

---

## 📜 License

This repository currently does not include an open-source license.
