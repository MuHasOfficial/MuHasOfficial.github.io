---
layout: post
title: Microcontroller-Based Smart Exhaust & Environmental Control System
description: Designed and prototyped an automated mechatronic exhaust system using a Raspberry Pi Pico W microcontroller, sensors, L298N driver, and an OLED telemetry display.
skills:
  - Raspberry Pi Pico
  - Embedded C/Python
  - Mechatronics
  - Sensor Integration
  - Circuit Design
---

### Project Overview
Designed and prototyped an automated mechatronic exhaust system driven by a Raspberry Pi Pico W microcontroller. The system automatically monitors ambient environmental factors using temperature and humidity sensors, displaying real-time data—such as temperature and system status—on an OLED display.

## Key Engineering Contributions
- **Thermal & System Architecture**: Designed a temperature-controlled exhaust fan system, using a Raspberry Pi Pico 2W microcontroller, an AHT10 environmental sensor, and an L298N motor driver to accurately manage thermal thresholds.
- **Circuit Design & Prototyping**: Engineered electrical circuit layouts on a breadboard and simulated connections in Multisim, handling power distribution, MOSFET/driver switching logic, and OLED display integration for real-time sensor telemetry.
- **Embedded Firmware & Integration**: Developed and deployed Python/MicroPython control scripts to process real-time environmental data from the AHT10 sensor and modulate fan speeds via PWM through the L298N driver based on active temperature feedback.

## Project Gallery

{% include image-gallery.html images="exh1.png, exh2.png" height="400" %}

### Summary
I designed and prototyped an automated mechatronic exhaust system driven by a Raspberry Pi Pico W microcontroller. The system actively monitors the environment using integrated sensors, displaying real-time data—such as temperature, humidity, and system status—on an OLED display. Developed custom control logic to dynamically adjust cooling and exhaust fan speeds based on threshold triggers, combining embedded firmware programming, breadboard circuit design, and hardware actuation. 


