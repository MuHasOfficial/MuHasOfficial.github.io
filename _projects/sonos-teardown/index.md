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

main-image: /exh2.png
---


## Key Engineering Contributions
- **Thermal & System Architecture**: Designed a temperature-controlled exhaust fan system, using a Raspberry Pi Pico 2W microcontroller, an AHT10 environmental sensor, and an L298N motor driver to accurately manage thermal thresholds.
- **Circuit Design & Prototyping**: Engineered electrical circuit layouts on a breadboard and simulated connections in Multisim, handling power distribution, MOSFET/driver switching logic, and OLED display integration for real-time sensor telemetry.
- **Embedded Firmware & Integration**: Developed and deployed Python/MicroPython control scripts to process real-time environmental data from the AHT10 sensor and modulate fan speeds via PWM through the L298N driver based on active temperature feedback.

## Project Gallery

<div class="gallery-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px;">

  {% assign folder_path = page.path | split: "/" | slice: 0, 2 | join: "/" %}

  <figure style="text-align: center; margin: 0; background-color: #1e1e1e; border-radius: 8px; padding-bottom: 12px; overflow: hidden;">
    <img src="/{{ folder_path }}/microsevroset.png" alt="Micro Servo Setup" style="width: 100%; height: 280px; object-fit: contain; background-color: #1e1e1e; display: block;">
    <figcaption style="margin-top: 10px; font-size: 14px; color: #f0f0f0; padding: 0 10px;">
      Raspberry Pi Pico W2 setup with a servo motor connecting the fans 
    </figcaption>
  </figure>

  <figure style="text-align: center; margin: 0; background-color: #1e1e1e; border-radius: 8px; padding-bottom: 12px; overflow: hidden;">
    <img src="/{{ folder_path }}/outexh.png" alt="Outer Exhaust View" style="width: 100%; height: 280px; object-fit: contain; background-color: #1e1e1e; display: block;">
    <figcaption style="margin-top: 10px; font-size: 14px; color: #f0f0f0; padding: 0 10px;">
      Outer view of the exhaust system installation and fit into a cardboard box.
    </figcaption>
  </figure>

</div>


