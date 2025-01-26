# Electron-Python-Arduino Integrator

## Project Overview
This project demonstrates the integration of Electron, Python, and Arduino to create a desktop application for hardware control and monitoring. The application provides a user-friendly GUI built with Electron, a Node.js backend for communication, and Python for bridging software and hardware interactions via the Arduino board. The system is designed for seamless real-time data visualization and control of connected sensors and actuators.

---

## Features
- **Interactive GUI:** Developed using Electron for controlling hardware and displaying data.
- **Arduino Integration:** Commands sent from the app to control sensors and actuators in real time.
- **Python Middleware:** Utilizing the `pyFirmata` library for robust communication between the app and the Arduino.
- **Node.js Backend:** Manages serial communication and acts as the middleware for the Electron frontend.
- **Real-time Monitoring:** Data from sensors is displayed in real-time through the GUI.

---

## Architecture
1. **Frontend (Electron):**
   - Provides a clean user interface with options to send commands and view sensor data.
   - Built with HTML, CSS, and JavaScript.

2. **Backend (Node.js):**
   - Handles serial communication with Arduino using libraries like `serialport`.
   - Facilitates data flow between the Electron frontend and Python middleware.

3. **Middleware (Python):**
   - Implements the `pyFirmata` library for communication with Arduino.
   - Processes sensor data and executes control logic as required.

4. **Hardware (Arduino):**
   - Interfaces with sensors and actuators.
   - Executes commands received from the software layers and sends feedback.

----

## Prerequisites
1. **Software Requirements:**
   - Node.js (v18 or later)
   - Python 3.13 with `pyFirmata`
   - Arduino IDE (for initial board setup)
   - Electron (latest version)
   
2. **Hardware Requirements:**
   - Arduino board (e.g., Uno, Mega, or compatible board)
   - Sensors/Actuators (customized to your application)
   - USB cable for Arduino connection

----


