# 🔔 Door Opening Alarm using Hall Sensor

A simple electronics project that detects when a door is opened using a **Hall-effect sensor and a permanent magnet**. When the door opens, the circuit activates a **buzzer and LED** as an alert.

## 📌 Project Overview

This project demonstrates how a Hall-effect sensor can be used for **magnetic field detection** and how transistor-based switching can control an alarm output.

The project can be used as a basic **door-opening detection and security system**.

## ⚙️ Working Principle

1. A permanent magnet is placed on the moving part of the door.
2. The **MH183 Hall-effect sensor** is positioned on the door frame.
3. When the door is closed, the magnet remains close to the sensor and the alarm remains OFF.
4. When the door is opened, the magnet moves away from the sensor.
5. The Hall sensor output changes.
6. The transistor switching circuit responds to this change.
7. The **buzzer and LED are activated**, indicating that the door has been opened.

### Basic Flow

```text
Door Closed
     ↓
Magnet near Hall Sensor
     ↓
Alarm OFF

Door Opened
     ↓
Magnet moves away
     ↓
Hall Sensor Output Changes
     ↓
Transistor Switching Circuit
     ↓
Buzzer + LED ON
