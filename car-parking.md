# 🚗 Smart Car Parking System

> **Status:** ✅ Completed

An IoT-based Smart Car Parking System that automates vehicle entry using ultrasonic sensors and an Arduino Uno. The system detects approaching vehicles and automatically opens the parking barrier by rotating a servo motor, demonstrating the integration of sensors, microcontrollers, and automation.

---

## 🚀 Overview

The Smart Car Parking System was developed to automate vehicle entry into a parking area. Using ultrasonic sensors, the system detects the presence of a vehicle and triggers a servo motor to rotate the barrier by 90 degrees, allowing the vehicle to enter without manual intervention.

The project demonstrates the fundamentals of embedded systems, sensor integration, and hardware automation using Arduino.

---

## ✨ Features

- Automatic vehicle detection
- Contactless parking gate operation
- Ultrasonic sensor-based distance measurement
- Servo motor controlled barrier movement
- Real-time automated response
- Simple and efficient embedded system design

---

## 🛠 Tech Stack

### Hardware
- Arduino Uno
- Ultrasonic Sensor
- Servo Motor

### Software
- Arduino IDE
- Python

---

## ⚙️ How It Works

1. The ultrasonic sensor continuously monitors the distance in front of the parking gate.
2. When a vehicle enters the detection range, the sensor sends distance measurements to the Arduino Uno.
3. The Arduino processes the sensor data and determines whether a vehicle is present.
4. If a vehicle is detected, the servo motor rotates the barrier by 90 degrees, allowing the vehicle to enter.
5. After the vehicle passes, the barrier returns to its original position, ready for the next vehicle.

---

## 🧠 Core Components

### Vehicle Detection
- Uses an ultrasonic sensor to detect approaching vehicles based on distance measurements.

### Control Unit
- Arduino Uno processes sensor input and controls system behavior.

### Barrier Automation
- Servo motor rotates the parking barrier automatically when a vehicle is detected.

---

## 🎯 Learning Objectives

This project demonstrates the fundamentals of IoT and embedded systems by integrating sensors, microcontrollers, and actuators to automate a real-world parking access scenario.

---

## 🔮 Future Improvements

- Display available parking slots using an LCD
- RFID-based authorized vehicle access
- Mobile application for parking monitoring
- Cloud-based parking analytics
- Automatic parking slot counting
- License plate recognition using computer vision
- Real-time occupancy monitoring

---

## 👩‍💻 Author

Developed by **Sunaina** as an IoT project demonstrating sensor integration, embedded programming, and hardware automation using Arduino Uno.
