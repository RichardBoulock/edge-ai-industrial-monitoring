# edge-ai-industrial-monitoring
Industrial Edge AI Monitoring Platform | STM32U585 • Arduino Nano 33 BLE Sense • Arduino Uno Q • TinyML • Predictive Maintenance

# Edge AI Industrial Monitoring Platform

## Multi-Board Edge AI System for Industrial Monitoring

This project explores an industrial Edge AI architecture using several embedded platforms:

- Arduino Nano 33 BLE Sense for TinyML sensor classification
- STM32U585 for embedded AI inference
- Arduino Uno Q with Qualcomm Dragonwing QRB2210 as a Linux-based Edge AI gateway
- Local dashboard for monitoring, logging and alerting

---

## Objective

Design and document a complete Edge AI monitoring platform capable of:

- collecting sensor data
- running local inference
- detecting anomalies
- communicating between edge devices
- visualising system status
- supporting predictive maintenance scenarios

---

## System Architecture

```text
Arduino Nano 33 BLE Sense
        ↓
IMU / Sensor Data Classification
        ↓
MQTT / Serial Communication
        ↓
Arduino Uno Q Linux Gateway
        ↓
Dashboard / Logging / Alerts
        ↓
STM32U585 AI Inference Node
        ↓
Anomaly Detection / Classification
