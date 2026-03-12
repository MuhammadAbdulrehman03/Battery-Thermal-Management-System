# 🔋 Battery Thermal Management System (BTMS) for EV Applications

![Project Status](https://img.shields.io/badge/status-in%20progress-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📌 Overview

This project investigates **thermal management challenges in electric vehicle batteries**, specifically for high-ambient-temperature conditions (like Pakistan's 40-45°C summers). I designed, built, and tested a prototype Battery Thermal Management System using an 8-cell 4S2P lithium-ion battery module with Arduino-based monitoring and smart cooling control.

**Why this matters:**
EV batteries in hot climates face reduced performance, faster degradation, and safety risks. This project explores practical cooling solutions and provides experimental data on thermal behavior.

## 🎯 Key Features

- ✅ 8-cell 4S2P lithium-ion battery module (14.8V, 6Ah)
- ✅ Multi-point temperature monitoring (5 sensors)
- ✅ Smart automatic fan control (ON/OFF at thresholds)
- ✅ Data logging capability
- ✅ Experimental comparison: no cooling vs fan cooling
- ✅ Thermal hotspot analysis
- ✅ Designed for hot climate conditions

## 🛠️ Technologies Used

- **Hardware:** 18650 lithium cells, 4S BMS, Arduino Nano, DS18B20/KY-028 sensors, 12V fans, relay module
- **Software:** Arduino IDE, C++, Python (for data plotting), Excel
- **Tools:** Multimeter, power supply, load resistors

## 📊 Experiments Conducted

| Experiment | Description | Key Finding |
|------------|-------------|-------------|
| 1 - No Cooling | Battery discharged at 5A without cooling | Center cells reached 45°C in 20 min |
| 2 - Fan Cooling | Continuous fan during discharge | Temperature reduced by 8°C |
| 3 - Smart Control | Fan auto ON/OFF at 40°C/35°C | 40% energy savings vs continuous fan |
| 4 - Hot Climate Simulation | Ambient heated to 40°C | Cooling effectiveness reduced by 60% |

## 🔧 System Architecture
