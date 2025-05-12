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

## Installation

**1.Clone this repository** to your local machine:

   ```bash
   https://github.com/TVARSHINI2904/assignment.git

 **2.Install required libraries** via Arduino Library Manager:
-**Blynk**
-**PubSubClient**
-**Adafruit SSD1306**
-**Adafruit GFX**
-**DallasTemperature**
-**OneWire**

3.**Open the Arduino sketch** in Arduino IDE and update the following:
- Wi-Fi SSID and Password
- BLYNK_TEMPLATE_ID **"TMPL39sshMipF"**
- BLYNK_TEMPLATE_NAME **"heat controller"**
- BLYNK_AUTH_TOKEN **"e8Xm8OQs4QUUITtZawrQiBA-k2H5zdc_"**
  
 **4.Select Board** Choose ESP32 Dev Module under Tools > Board.

**5.Upload the code to your ESP32.**



