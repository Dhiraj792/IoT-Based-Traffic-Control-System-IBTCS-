# 🔧 Hardware

This folder contains all the hardware-related documents and resources for the **IoT-Based Traffic Control System** project.

It includes circuit designs, wiring references, component details, and hardware specifications required to build and understand the system.

---

## 📂 Contents

- 📄 Circuit Diagram
- 🔌 Wiring Diagram
- 📋 Components List
- 📦 Bill of Materials (BOM)

---

## 🖥️ Main Controller

- **ESP32 Dev Module**
  - Acts as the primary controller.
  - Handles IoT communication and system coordination.
  - Communicates with the Arduino UNO via UART.

---

## 🎛️ Secondary Controller

- **Arduino UNO**
  - Controls hardware peripherals.
  - Processes sensor inputs.
  - Operates the servo motors for traffic signal control.

---

## 📡 Sensors Used

- **IR Sensor**
  - Detects the presence of vehicles.
  - Measures traffic density.

- **Sound Sensor**
  - Detects emergency vehicle sirens.
  - Triggers priority-based traffic signal control.

---

## ⚙️ Actuators

### SG90 Servo Motors

Used to simulate the opening and closing of traffic barriers or to control the direction of traffic signals.

---

## 🔗 Communication

The two microcontrollers communicate using:

- **UART Serial Communication**
  - ESP32 ↔ Arduino UNO
  - Ensures reliable data exchange between the controllers.

---

## 🔋 Power Supply

The hardware is powered using:

- **5V Regulated Power Supply**
- **Buck Converter** for stable voltage regulation

---

## 📌 Hardware Summary

| Component | Purpose |
|-----------|---------|
| ESP32 Dev Module | Main IoT Controller |
| Arduino UNO | Hardware Control |
| IR Sensor | Vehicle Detection |
| Sound Sensor | Emergency Vehicle Detection |
| SG90 Servo Motor | Traffic Barrier / Signal Control |
| UART | Controller Communication |
| Buck Converter | Voltage Regulation |

---

## 📁 Folder Purpose

This folder serves as the central location for all hardware documentation required to assemble, understand, and maintain the IoT-Based Traffic Control System.
