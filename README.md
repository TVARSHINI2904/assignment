# assignment

# Heater Control System with Blynk, MQTT, and OLED Display

This project is a temperature-based heater control system that uses an ESP32 to control a heater based on the ambient temperature. The system also integrates Blynk for remote control, MQTT for communication, and an OLED display for monitoring the system's status.

## Features

- **Temperature Monitoring**: The system monitors temperature using a Dallas DS18B20 sensor.
- **Heater Control**: Based on the temperature, the system can turn the heater on or off.
- **State Management**: Displays the system state on Blynk (Idle, Heating, Stabilizing, Target Reached, Overheat).
- **MQTT Communication**: The system sends temperature readings and state updates via MQTT.
- **OLED Display**: Displays the current temperature, system state, WiFi status, and MQTT connection status.
- **Remote Control**: Use the Blynk app to control the system remotely (on/off, state changes).

## Hardware Requirements

- **ESP32** (or any compatible microcontroller with WiFi support)
- **Dallas DS18B20 Temperature Sensor**
- **OLED Display** (128x64, I2C)
- **Relay Module** (to control the heater)
- **Buzzer** (for overheat condition)
- **Slide Switch** (to manually control the system)
- **WiFi Router** for internet connection
- **MQTT Broker** (Tested with Mosquitto Broker)

## Software Requirements

- **Arduino IDE** (with ESP32 board support)
- **Blynk Library** for ESP32
- **PubSubClient** for MQTT
- **Adafruit SSD1306** for OLED display
- **DallasTemperature** for temperature sensor control
- **OneWire** for communication with DS18B20 senso

