# ECG and Pulse Oximeter Monitoring System

This project implements a portable ECG (Electrocardiogram) and Pulse Oximeter monitoring system using open-source hardware tools. It is designed for real-time monitoring of heart rhythms and blood oxygen levels, offering a cost-effective solution for health diagnostics.

## Motivation

Cardiovascular and respiratory health are critical indicators of well-being. Accurate and continuous monitoring of ECG signals and oxygen saturation (SpO2) helps detect abnormalities early, especially for patients with heart or lung conditions. This project aims to develop a compact, reliable, and affordable health monitoring device using Arduino, NodeMCU, and sensor modules like AD8232 and MAX30100.

## Key Features

- Real-time ECG signal acquisition

- Continuous monitoring of pulse rate and SpO2 levels

- Display of heart rate and oxygen levels via serial monitor or IoT

- Portable and low-cost hardware implementation

# Components Used

Arduino Uno - Microcontroller board for ECG signal processing

AD8232 ECG Sensor - For acquiring ECG signals

MAX30100 Sensor - For pulse rate and SpO2 monitoring

NodeMCU ESP8266 - WiFi-enabled microcontroller for IoT support

Jumper wires, breadboard, power supply

# Project Workflow

1.Data Acquisition

ECG signal from AD8232 sensor

Pulse rate and SpO2 from MAX30100 sensor

2.Microcontroller Interface

Arduino Uno processes ECG data

NodeMCU processes and transmits pulse/oxygen data via WiFi

3.Signal Processing & Display

ECG displayed as analog wave via serial monitor

Pulse/SpO2 values displayed numerically


