# Project Title: RagTag - RideEnviro Monitor System

## Overview

RagTag is a compact environmental monitoring gadget designed specifically for motorbike riders, focusing on simplicity and affordability. This DIY project aims to provide real-time data (temperature, atmospheric pressure, altitude changes) directly to the rider through an easy-to-install device, enhancing their riding experience by offering crucial insights without the complexity of professional systems.

### Project Motivation

Inspired by the need for affordable yet informative monitoring tools in simpler motorbike setups lacking advanced telemetry features, RagTag was conceptualized. The project emphasizes ease of installation and operation, making it accessible to amateur riders who wish to understand their riding conditions better without significant investment in sophisticated equipment.

## Features Tailored Specifically for Motorbike Riders

- **Dual-Bus Configuration**: Utilizes dual I2C bus capabilities of the ESP32 to manage sensor data efficiently, minimizing latency.
- **User Interaction**: Simple button interface allows easy navigation through displays showing temperature, pressure, altitude, and system uptime in real-time.

## Transition Plan: From ESP32 S3 N16R8 to ESP32 C3

Following successful development on the ESP32 S3 N16R8 microcontroller, the next phase involves transitioning to a more compact and cost-effective ESP32 C3. This transition aims to refine RagTag into an even more streamlined version without compromising its core functionalities, focusing on reduced size and lower production costs.

## Installation & Setup Guide

1. **Wiring**: Connect the BMP280 sensor and OLED display to the ESP32 microcontroller as per standard I2C configurations.
2. **Software Upload**: Utilize USB-C connection to upload the `ragtag_usb_c.ino` sketch, ensuring compatibility with both current (ESP32 S3) and anticipated (ESP32 C3) firmware updates.
3. **Initial Configuration**: Navigate through the OLED display menus using the button interface for initial setup parameters like refresh intervals.

## Technical Documentation Simplified

### Initialization & Data Acquisition Overview
The `setup()` function initializes serial communication, configures sensor interfaces on their I2C buses, and sets up the OLED display for data visualization. The main loop coordinates real-time data fetching from sensors at predefined intervals to ensure minimal latency in readings.

### User Interaction Mechanism
A debounced button mechanism facilitates mode changes (overview, temperatures, altitude, pressure) through straightforward electrical logic without requiring specialized inputs on the motorbike's control panel.

## Conclusion

RagTag embodies a commitment to merging technological advancement with practical utility, particularly within niche sectors like motorbike enthusiasts seeking reliable yet affordable environmental monitoring solutions. Its evolution from prototype to potential mass production underscores an ethos towards innovation that resonates deeply with challenges faced by motorcycle riders worldwide in understanding and optimizing their riding conditions.

For those looking to customize or delve deeper into the firmware specifics, sensor calibration guides, or comprehensive operational manuals tailored for developmental stages as well as production readiness, refer to the respective documentation outlines provided under each parameter setting. These materials aim not just at immediate deployment but also at fostering a community-driven approach towards enhancing RagTag's capabilities and broader applicability in real-world motorbike riding scenarios.