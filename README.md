# Smart Gas Leakage Monitoring System

An IoT-based gas leakage monitoring system developed to detect hazardous gas levels in real time and provide both local alerts and remote cloud monitoring.

## Project Overview

The system uses an ESP32 microcontroller and MQ135 gas sensor to continuously monitor gas concentration levels. Sensor readings are processed by the ESP32 and transmitted to the ThingSpeak cloud platform through WiFi using the HTTP protocol.

When the gas concentration exceeds the predefined safety threshold, the system automatically activates a red LED and buzzer to alert users. Under safe conditions, a green LED remains active.

## Key Features

- Real-time gas concentration monitoring
- Automatic hazardous gas detection
- LED visual indicators for safe and hazardous conditions
- Buzzer alert when gas levels exceed the safety threshold
- Real-time data transmission to ThingSpeak
- Remote cloud-based monitoring and data visualization
- Automatic recovery to safe mode when gas levels return to normal

## Technologies & Components

- ESP32
- MQ135 Gas Sensor
- Arduino C/C++
- Arduino IDE
- ThingSpeak
- WiFi
- HTTP Protocol
- LED Indicators
- Buzzer

## System Testing

The system was tested under normal and gas-exposure conditions. During testing, normal readings remained approximately between 550–600, while gas exposure produced readings of approximately 685–761. The system successfully activated the warning mechanism when readings exceeded the predefined threshold of 600.

## Project Report

The complete project report, including the system architecture, circuit design, implementation, testing, and results, is available in the `docs` folder.

## Academic Project

**Course:** IoT and Cloud Computing  
**Programme:** Bachelor in Information Technology (Hons.)  
**University:** Universiti Selangor (UNISEL)
