# Sun-Tracker-Solar-system-controller
Complete Solar Power Control System with Sun Tracking Functionality A fully integrated solar power management system featuring automatic sun tracking, battery charge regulation, power distribution control, and real-time performance monitoring. Designed using microcontrollers, sensors, and motor drivers for efficient renewable energy harvesting.

# 🌞 Complete Solar Power Control System with Sun Tracking Functionality

This project is a **comprehensive solar power management and control system** that includes a **dual-axis sun tracker**, **battery charging unit**, and **power distribution controller**.  
It is designed to **maximize solar panel efficiency** by continuously adjusting panel orientation based on sunlight intensity while ensuring optimal energy storage and usage.

---

## ⚙️ Features

- 🔆 **Automatic Sun Tracking:**  
  Dual-axis tracking system (azimuth and elevation) using LDR sensors and servo motors.  

- ⚡ **Power Control and Regulation:**  
  Smart charging algorithm with overcharge and deep-discharge protection.  

- 🔋 **Battery Management:**  
  Real-time monitoring of voltage, current, and temperature to ensure safe operation.  

- 🧭 **Microcontroller-Based Control:**  
  Implemented using an **AVR MCU** for flexibility and real-time response.  

- 🖥️ **Display & Monitoring:**  
  LCD interface to display voltage, current, panel angle, and system status.  

---

## 🧩 Hardware Components

| Component | Description |
|------------|-------------|
|2 *  Solar Panel | 15W PV panel |
| 4 * LDR Sensors | For light intensity detection |
| 2 * Servo Motors | For dual-axis tracking |
| 1 * Microcontroller | AMega32 smd |
| Motor Drivers | PWM |
|1 * Battery | 12V Lead-acid |
| Voltage Sensors | ADC of MCU |
| 1 * Display | 16x2 LCD |
| Misc. | Resistors, Diodes, MOSFETs, Fuses, Relays |

---

## 🧠 Working Principle

1. **Sensing:**  
   Four LDR sensors placed in a cross pattern detect sunlight direction by a differential algorithm.  

2. **Tracking:**  
   The controller compares sensor outputs and adjusts motor angles to maximize light intensity.  

3. **Power Regulation:**  
   The charge controller ensures safe and efficient charging of the connected battery and checks the battery's voltage level real-time.  

4. **Load Management:**  
   Power is distributed to connected to a 12 to 220V inverter.  

---

## 💻 Software Overview

- Written in **C /CV AVR**
- Modular code structure for easy debugging
- PID-based control loop for smooth motor movement
- ADC-based voltage and current measurement

---

## 📊 Future Improvements

- Integration with **MPPT algorithms**
- Real-time data visualization via web dashboard
- Machine learning-based predictive sun tracking
- Hybrid power management (solar + wind)

---

## 🧑‍💻 Author

**Alireza Eskandari**  
M.Sc. in Electronic Engineering – Space Communication and Sensing  
University of Pavia, Italy  

📧 alireza.eskandari@email.com  
🔗 [GitHub Profile](https://github.com/yourusername)

---
