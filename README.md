# SURVEILLANCE-ROVER
An ESP32-based Wi-Fi controlled surveillance rover featuring dual-power management, real-time wireless video streaming, and OpenCV-based human tracking and target zoom.

# ESP32-CAM & OpenCV-Powered Real-Time Surveillance Rover 🤖📹
An advanced IoT and computer vision project that combines embedded hardware peripherals with real-time image processing. Built as part of my engineering journey, focusing on embedded systems, hardware integration, and edge intelligence.
---
## 🚀 Key Features
* **Wireless Control & Streaming:** Low-latency motor control and live video feed transmitted over a local Wi-Fi network using an ESP32-CAM module.
* **Computer Vision (OpenCV Integration):** Real-time human detection, pose estimation, and dynamic Region of Interest (ROI) tracking with a dedicated "Target Zoom" window.
* **Robust Dual-Power Architecture:** 
  * Dedicated **5V Power Bank** for microcontrollers to prevent voltage drops and system brownouts.
  * Separate **3x 18650 Li-ion battery pack** connected via an L298N motor driver to drive high-current DC motors safely.
---
## 🛠️ Hardware Components
1. **ESP32 Microcontroller:** Acts as the primary control node for Wi-Fi communication and PWM signal generation.
2. **ESP32-CAM (OV2640 Sensor):** Handles image capture and hosts the local video streaming web server.
3. **L298N Dual H-Bridge Motor Driver:** Translates low-voltage logic signals from the ESP32 into high-current power for the motors.
4. **DC Geared Motors:** Provide necessary torque for rough terrain navigation.
5. **Power Supply Modules:** Split architecture separating logic and motor power rails.
---
## 💻 Software Stack
* **Firmware:** Arduino IDE (C/C++) for ESP32 and ESP32-CAM configuration.
* **Computer Vision & Processing:** Python, OpenCV for real-time human detection and tracking overlays.
---
## 📸 System Overview & Tracking Feed

| Rover Hardware Assembly | OpenCV Real-Time Human Tracking & Zoom |
| :--- | :--- |
| ![Rover Hardware](rover%20image.jpeg) | ![OpenCV Tracking](camera%20feed.png) |
---

### 🎥 Project Demo Video
[![Watch Rover Video](https://img.shields.io/badge/Click%20To%20View-Project%20Demo%20Video-blue?style=for-the-badge&logo=microsoftonedrive)](https://1drv.ms/i/c/BFC31027103C6E71/IQCAq6GuGwpAQ7bUg4nbkbDSAZQpB_DGV_qNiKtHCNqhKpA?e=DrxDbX)

## 📐 Circuit Diagram & Connections
Refer to the documentation and circuit schematics included in the repository for detailed pin configurations between the ESP32, ESP32-CAM, and L298N motor driver.
---
## 👤 Author
**Shubham**  
