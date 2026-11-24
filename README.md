# Smart-EV-Monitoring-and-Anti-Theft-System
ESP32 based EV monitoring and anti-theft system using IoT
Smart EV Monitoring and Anti-Theft System using IoT

Project Overview

This project is developed using an ESP32 microcontroller to monitor EV charging conditions, analyse driver behaviour and detect unauthorised vehicle movement.

Main Modules

# 1. EV Charging Monitoring

Monitors simulated charging voltage, current and temperature and detects abnormal charging conditions.

# 2. Driver Behaviour Analysis

Analyses simulated acceleration, sudden braking and excessive motor load.

# 3. Theft Detection

Activates security mode when the vehicle is parked. Detects movement using a PIR sensor and activates a buzzer alarm.

# Components Used

- ESP32 DevKit V1
- LCD 16x2 I2C
- Five potentiometers
- PIR motion sensor
- Buzzer
- Three LEDs
- Two push buttons
- Resistors

Software Used

- Wokwi Simulator
- Arduino IDE
- ESP32
- Blinker IoT

# Working

The ESP32 reads simulated sensor values and analyses the vehicle's charging and security conditions. It displays the system status on an LCD and Serial Monitor and supports remote monitoring through the Blinker IoT dashboard.

# Project Status

Prototype simulation using Wokwi.
