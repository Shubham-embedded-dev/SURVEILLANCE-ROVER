# SURVEILLANCE-ROVER
An ESP32-based Wi-Fi controlled surveillance rover featuring dual-power management, real-time wireless video streaming, and OpenCV-based human tracking and target zoom.

# ESP32-CAM & OpenCV-Powered Real-Time Surveillance Rover 🤖📹
An advanced IoT and computer vision project that combines embedded hardware peripherals with real-time image processing. Built as part of my engineering journey, focusing on embedded systems, hardware integration, and edge intelligence[span_4](start_span)[span_4](end_span)[span_5](start_span)[span_5](end_span).
---
## 🚀 Key Features
* **Wireless Control & Streaming:** Low-latency motor control and live video feed transmitted over a local Wi-Fi network using an ESP32-CAM module[span_6](start_span)[span_6](end_span)[span_7](start_span)[span_7](end_span).
* **Computer Vision (OpenCV Integration):** Real-time human detection, pose estimation, and dynamic Region of Interest (ROI) tracking with a dedicated "Target Zoom" window[span_8](start_span)[span_8](end_span).
* **Robust Dual-Power Architecture:** 
  * Dedicated **5V Power Bank** for microcontrollers to prevent voltage drops and system brownouts[span_9](start_span)[span_9](end_span).
  * Separate **3x 18650 Li-ion battery pack** connected via an L298N motor driver to drive high-current DC motors safely[span_10](start_span)[span_10](end_span).
---
## 🛠️ Hardware Components
1. **ESP32 Microcontroller:** Acts as the primary control node for Wi-Fi communication and PWM signal generation[span_11](start_span)[span_11](end_span).
2. **ESP32-CAM (OV2640 Sensor):** Handles image capture and hosts the local video streaming web server[span_12](start_span)[span_12](end_span)[span_13](start_span)[span_13](end_span).
3. **L298N Dual H-Bridge Motor Driver:** Translates low-voltage logic signals from the ESP32 into high-current power for the motors[span_14](start_span)[span_14](end_span).
4. **DC Geared Motors:** Provide necessary torque for rough terrain navigation[span_15](start_span)[span_15](end_span).
5. **Power Supply Modules:** Split architecture separating logic and motor power rails[span_16](start_span)[span_16](end_span).
---
## 💻 Software Stack
* **Firmware:** Arduino IDE (C/C++) for ESP32 and ESP32-CAM configuration.
* **Computer Vision & Processing:** Python, OpenCV for real-time human detection and tracking overlays[span_17](start_span)[span_17](end_span).
---
## 📸 System Overview & Tracking Feed

| Rover Hardware Assembly | OpenCV Real-Time Human Tracking & Zoom |
| :--- | :--- |
| ![Rover Hardware](39080.jpg) | ![OpenCV Tracking](40272.jpg)[span_18](start_span)[span_18](end_span) |

---
## 📐 Circuit Diagram & Connections
Refer to the documentation and circuit schematics included in the repository for detailed pin configurations between the ESP32, ESP32-CAM, and L298N motor driver[span_19](start_span)[span_19](end_span).
---
## 👤 Author
**Shubham**  
