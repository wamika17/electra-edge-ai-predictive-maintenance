# Firmware

This folder contains the embedded firmware running on the ESP32.

The firmware acquires machine parameters, processes sensor readings, and publishes data to the cloud dashboard through MQTT.

---

## Firmware Modules

- Sensor Initialization
- Current Monitoring
- MQTT Communication
- Machine Status Monitoring
- Relay Control

---

## Workflow

Initialize Sensors

↓

Acquire Machine Data

↓

Publish MQTT Data

↓

Repeat
