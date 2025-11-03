# AI Camera Module (ESP32-S3 & BNO085)

This is a personal hardware project for a compact, AI-powered camera module. The goal is to create a versatile IoT device for real-time motion tracking, AI-based gesture recognition, and Wi-Fi video streaming.

This repository contains the hardware design files for the project.

## Key Hardware Components
* **Main Processor:** ESP32-S3-MINI-1 (for Wi-Fi, Bluetooth, and AI processing)
* **Motion Sensor:** BNO085 9-axis IMU (Accelerometer, Gyroscope, Magnetometer)
* **Image Sensor:** Standard camera connector
* **Storage:** MicroSD card slot for local data storage
* **Power:** Complete power supply system with a LiPo battery charging circuit (MCP73831T) and LDOs for 3.3V and 1.2V rails.

## Intended Features (Firmware)
* Real-time motion tracking using the 9-axis IMU
* AI-based gesture recognition
* Wi-Fi video streaming
* Over-the-Air (OTA) firmware updates

## Project Status
* **Schematic:** 100% Complete
* **PCB Layout:** 50% Complete (In Progress)

## Files
* `9_AXIS_AI_CAMERA_MODULE_013-07-2025 FINAL SCHEMATIC.pdf`: The complete PDF schematic for the hardware.
