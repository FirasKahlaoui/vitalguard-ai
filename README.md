# VitalGuard-AI

## Overview
VitalGuard-AI is an intelligent patient monitoring system designed to enhance healthcare safety through real-time data acquisition, artificial intelligence, and predictive analytics.  
The system is built around ESP32 microcontrollers and biomedical sensors to continuously monitor patient vital signs and room conditions, while AI models analyze data to generate daily reports and predict potential health risks.

An optional computer vision module enables patient fall detection to improve response time in critical situations.

---

## Key Features
- Real-time patient vital sign monitoring
- Environmental monitoring of room conditions
- AI-generated daily patient health reports
- Anomaly detection and predictive risk analysis
- Optional fall detection using camera and computer vision
- Web-based dashboard with alerts and historical data
- Secure data storage and access control

---

## System Architecture
The system follows a layered architecture:
- **Sensor Layer**: Collects physiological and environmental data
- **Embedded Layer**: ESP32 handles data acquisition and transmission
- **Backend Layer**: API, database, and AI processing
- **Application Layer**: Web dashboard for visualization and alerts

---

## Hardware Components
- **ESP32**: Main microcontroller with Wi-Fi connectivity
- **MAX30102**: Heart rate and blood oxygen sensor
- **DHT22**: Temperature and humidity sensor
- **ESP32-CAM (Optional)**: Camera module for fall detection
- Protective enclosure suitable for hospital environments

---

## Software Stack
- Embedded C / Arduino framework for ESP32
- Backend API for data processing and storage
- Machine learning models for prediction and anomaly detection
- Computer vision models for fall detection
- Web dashboard for real-time monitoring and reports

---

## Artificial Intelligence Modules
- **Daily Report Generator**: Summarizes patient health data automatically
- **Predictive Model**: Detects abnormal patterns and potential risks
- **Fall Detection Model (Optional)**: Uses vision-based analysis to detect falls

---

## Data Collected
- Heart rate (BPM)
- Blood oxygen saturation (SpO₂)
- Room temperature (°C)
- Room humidity (%)
- Camera frames for fall detection (optional)

---

## Use Cases
- Continuous patient monitoring in hospital rooms
- Early detection of health deterioration
- Automated daily health reporting
- Rapid response to falls or abnormal conditions

---

## Project Status
This project is under active development as part of an academic and applied healthcare IoT initiative.

---

## Authors
- Firas Kahlaoui  
- Seifdine Ben Fradj  
- Hamza Bargoug  
- Ahmed Chaabane  

---

## License
This project is intended for academic and educational use.
