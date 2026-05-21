
# SkyPredict: Smart Weather Monitoring & Prediction System

SkyPredict is a smart weather monitoring and prediction system that combines embedded systems, sensor integration, and machine learning to provide accurate environmental monitoring and weather forecasting.

The project was developed using Arduino-based hardware, multiple environmental sensors, and a Naive Bayes machine learning model.

---

# 📌 Project Overview

<img width="362" height="279" alt="Screenshot 2026-05-21 at 7 47 34 PM" src="https://github.com/user-attachments/assets/33d189e3-4500-4664-9ec7-096e6d8f05af" />

This system collects real-time environmental data such as:

- Temperature
- Humidity
- Atmospheric pressure
- Water detection

The collected data is processed and filtered using a Kalman Filter to improve accuracy.  
After preprocessing, the system uses a Naive Bayes machine learning model to predict weather conditions.

The project focuses on:

- Smart environmental monitoring
- Sensor data accuracy
- Weather prediction
- Energy efficiency
- Embedded systems integration

---

# ⚡ Features

- Real-time weather monitoring
- Temperature and humidity sensing
- Atmospheric pressure measurement
- Water/rain detection
- Kalman Filter data optimization
- Machine learning weather prediction
- Energy-efficient operation
- Arduino-based embedded system

---

# 🛠 Hardware Components

- Arduino board
- Temperature sensor
- Humidity sensor
- Pressure sensor
- Water detection sensor
- Breadboard
- Jumper wires
- Power supply module

---

# 💻 Software & Technologies

- Arduino IDE
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Machine Learning (Naive Bayes)
- Kalman Filter

---

# 🧠 How the System Works

## 1️⃣ Data Collection

Sensors continuously collect environmental data such as:

- Temperature
- Humidity
- Pressure
- Water presence

---

## 2️⃣ Data Filtering

The Kalman Filter is used to reduce noise and improve sensor accuracy.

This helps produce more stable and reliable readings.

---

## 3️⃣ Weather Prediction

The processed data is sent to a Naive Bayes machine learning model.

The model predicts weather conditions based on previously trained climate datasets.

---

## 4️⃣ Output & Monitoring

The system displays and stores environmental information and prediction results.

---

# 📊 Machine Learning Model

The project uses a Naive Bayes classifier trained on climate datasets.

### Achievements

- 84.2% prediction accuracy
- Confusion matrix evaluation
- ROC analysis validation

---

# 🔋 Energy Efficiency

The system was designed with energy optimization techniques including:

- Active/Sleep mode cycling
- Reduced power consumption
- Efficient sensor management

This reduced overall power consumption by approximately 50%.

