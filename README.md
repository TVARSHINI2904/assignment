# Smart Heater Control System with ESP32

This project demonstrates the design and implementation of a **Smart Heater Control System** using the **ESP32 microcontroller**. The system is designed to regulate the temperature based on real-time data from a **DS18B20 temperature sensor**, and manage the heater's operation using a **relay module**. It supports **remote monitoring** and control via **Blynk IoT** and **MQTT** protocols, providing real-time updates on temperature and system state.

## Features

- **Temperature Monitoring**: Uses DS18B20 temperature sensor for accurate temperature readings.
- **Control Logic**: Supports multiple operational states (Idle, Heating, Stabilizing, Target Reached, Overheat) for safe and efficient heater control.
- **Manual Control**: Includes a physical button (slide switch) to manually turn the heater on/off.
- **Overheating Protection**: Activates a buzzer alarm if the temperature exceeds the predefined limit.
- **Remote Monitoring**: Integrates Blynk IoT for mobile app control and MQTT for cloud-based updates.
- **OLED Display**: Displays the current temperature, state, and Wi-Fi status for real-time feedback.

## Hardware Required

- **ESP32** Microcontroller
- **DS18B20** Temperature Sensor
- **Relay Module** for Heater Control
- **Buzzer** for Overheating Alarm
- **OLED Display** (128x64)
- **Slide Switch** for manual heater control
- **Jumper Wires & Breadboard**

## Circuit Diagram

https://pdflink.to/project_image/


## Software Required

- **Arduino IDE** for programming the ESP32.
- **Blynk** app for remote monitoring and control.
- **PubSubClient** library for MQTT communication.
  
## IOT Integration
-**Blynk IoT Integration**
-**Real-Time Monitoring**
       - V0: Displays temperature.
       - V1: Displays system state.
-**Remote Control**
       - V2: Slide switch to turn system ON/OFF.
## System Workflow

- **Slide switch or Blynk switch**: toggles system ON/OFF.
- **DS18B20 reads temperature every second.**
- **Based on thresholds, heater is activated/deactivated through a relay.**
- **OLED updates live temperature, Wi-Fi, and state.**
- **Buzzer alerts if temperature exceeds safety threshold.**
- **Blynk/MQTT broadcasts live data.**

 - **BLYNK_TEMPLATE_ID** "TMPL39sshMipF"
 - **BLYNK_TEMPLATE_NAME** "heat controller"
 - **BLYNK_AUTH_TOKEN** "e8Xm8OQs4QUUITtZawrQiBA-k2H5zdc_"


## Installation

**Clone this repository** to your local machine:

   ```bash
   https://github.com/TVARSHINI2904/assignment.git

 
