# PCB-DESIGN-PROJECTS

This repository contains various embedded systems projects. Each project is stored in its respective branch along with Altium Designer files. Below is a detailed description of each project.

## 📡 Wireless Security Detector (4-Layer PCB Design)

**Description:**  
A 4-layer PCB designed for security systems. Powered by 220V AC, the system provides 12V and 5V DC outputs. It features motion detection, Wi-Fi data transmission, real-time clock (RTC), temperature display, and interaction with security camera feeds.

**Features:**
- 220V AC input, 12V and 5V DC outputs
- Motion detection
- Data transmission over Wi-Fi
- Real-time clock (RTC)
- Temperature sensor
- Interaction with security cameras

**Files Included:**
- Altium Designer PCB and schematic files
- Firmware source code

Branch: `wireless-security-detector-board`

---

## ⚡ Panel Meter Card

**Description:**  
A high-precision panel meter capable of measuring voltage and current. The measurements are collected via ADC, processed, and displayed on a 7-segment display using the MAX7219 IC. Additionally, data is transmitted to a computer via UART for real-time visualization and logging.

**Features:**
- High-precision voltage and current measurement
- Data acquisition via ADC
- Display using MAX7219 IC and 7-segment display
- Real-time data transmission via UART

**Files Included:**
- Altium Designer PCB and schematic files
- Firmware source code

Branch: `panel-meter-board`

---

## 🔌 Relay Test Card

**Description:**  
A versatile relay test board designed for testing different relays. It utilizes the ATMEGA328P microcontroller, AP63200WU driver, and CH340G converter. The board includes customizable filtering and selectable relay voltage options to enhance testing flexibility.

**Features:**
- ATMEGA328P microcontroller
- AP63200WU driver
- CH340G USB-Serial converter
- Customizable filtering
- Selectable relay voltage options

**Files Included:**
- Altium Designer PCB and schematic files
- Firmware source code

Branch: `relay-test-card`

---

## 📂 How to Use?

Each project is stored in its respective branch along with the relevant design files. To access a specific project, follow these steps:

```bash
# Clone the repository
git clone <repo-url>
cd <repo-name>

# Switch to the desired project branch
git checkout <branch-name>
```

You can open the schematic and PCB designs using Altium Designer and compile the firmware to run on the respective hardware.

---

📧 **Contact:** If you have any questions or suggestions for improvements, feel free to reach out!
