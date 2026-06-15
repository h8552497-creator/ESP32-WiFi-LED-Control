# ESP32 WiFi LED Control

## Overview

This project demonstrates how to control an LED wirelessly using an ESP32 development board. The ESP32 hosts a web server that allows users to turn an LED ON and OFF directly from a web browser.

The project is designed for beginners who want to learn ESP32 programming, IoT concepts, and web-based hardware control.

---

## Features

* Wireless LED Control
* Browser-Based Interface
* ESP32 Web Server
* Real-Time LED Switching
* Beginner Friendly
* Low-Cost Hardware

---

## Components Required

| Component       | Quantity  |
| --------------- | --------- |
| ESP32 DevKit V1 | 1         |
| LED             | 1         |
| 220Ω Resistor   | 1         |
| Breadboard      | 1         |
| Jumper Wires    | As Needed |

---

## Circuit Connections

LED Positive (+) → GPIO 2

LED Negative (-) → 220Ω Resistor → GND

---

## Libraries Required

No additional libraries are required.

Built-in WiFi library:

* WiFi.h

---

## How It Works

1. ESP32 connects to WiFi.
2. A web server starts on the ESP32.
3. The browser displays ON and OFF buttons.
4. User clicks a button.
5. ESP32 receives the request.
6. LED state changes instantly.

---

## Applications

* Smart Home Projects
* IoT Learning
* Wireless Control Systems
* Home Automation
* Educational Demonstrations

---

## Future Improvements

* Multiple LED Control
* Mobile-Friendly UI
* RGB LED Support
* Voice Control
* MQTT Integration
* Cloud Connectivity

---

## Author

Created by M

Subscribe for more ESP32, Arduino, Robotics, AI, Raspberry Pi, and Electronics Projects.
