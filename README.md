# vitalguard-ai

![ESP32](https://img.shields.io/badge/platform-ESP32-blue)
![IoT](https://img.shields.io/badge/domain-IoT-green)
![AI](https://img.shields.io/badge/AI-machine%20learning-orange)
![Status](https://img.shields.io/badge/status-active%20development-yellow)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## Overview
vitalguard-ai is an intelligent patient monitoring system designed to improve healthcare safety through real time data acquisition, artificial intelligence, and predictive analytics.

The system is built around ESP32 microcontrollers and biomedical sensors to continuously monitor patient vital signs and room conditions. Artificial intelligence models analyze the collected data to generate daily health reports, detect anomalies, and predict potential health risks.

An optional computer vision module enables patient fall detection to reduce response time in critical situations.

---

## Key Features
- Real time monitoring of patient vital signs
- Environmental monitoring of room temperature and humidity
- AI generated daily patient health reports
- Anomaly detection and predictive risk analysis
- Optional fall detection using camera and computer vision
- Web based dashboard with alerts and historical data visualization
- Secure data storage and role based access control

---

## System Architecture
The system follows a layered and scalable architecture:

- **Sensor Layer**  
  Collects physiological and environmental data from biomedical sensors

- **Embedded Layer**  
  ESP32 handles data acquisition, preprocessing, and wireless transmission

- **Backend Layer**  
  API, database, alert logic, and AI processing

- **Application Layer**  
  Web dashboard for real time monitoring, analytics, and reporting

---

## Hardware Components
- **ESP32**  
  Main microcontroller with integrated Wi Fi connectivity

- **MAX30102**  
  Heart rate and blood oxygen saturation sensor

- **DHT22**  
  Temperature and humidity sensor

- **ESP32 CAM (Optional)**  
  Camera module used for fall detection

- Protective enclosure suitable for hospital environments

---

## Software Stack
- Embedded C using Arduino framework for ESP32
- Backend API for data ingestion, processing, and storage
- Machine learning models for prediction and anomaly detection
- Computer vision models for fall detection
- Web dashboard for real time monitoring and report visualization

---

## Artificial Intelligence Modules
- **Daily Report Generator**  
  Automatically summarizes patient health data and trends

- **Predictive Model**  
  Identifies abnormal patterns and predicts potential health risks

- **Fall Detection Model (Optional)**  
  Vision based model that detects patient falls using camera input

---

## Data Collected
- Heart rate (BPM)
- Blood oxygen saturation (SpO2)
- Room temperature (°C)
- Room humidity (%)
- Camera frames for fall detection (optional)

---

## Use Cases
- Continuous patient monitoring in hospital rooms
- Early detection of patient health deterioration
- Automated daily health reporting for medical staff
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
This project is licensed under the MIT License.  
You are free to use, modify, and distribute this software with proper attribution.
