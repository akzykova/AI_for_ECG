# AI_for_ECG

**Course Work 2023 - 2024**

A project focused on analyzing Holter monitoring data using machine learning methods to detect anomalies related to ST-segment changes in ECG signals.

## About the Project

The goal of this project is to develop a system for analyzing ECG data to detect abnormal conditions such as myocardial infarction or ischemia by identifying changes in the ST-segment. The system utilizes machine learning to process 24-hour ECG recordings and detect anomalous heartbeats.

## Tasks

- Calculate heart rate variability.
- Create spectrograms of Holter monitoring data.
- Segment 24-hour recordings into individual heartbeats.
- Develop and train models to detect anomalies in ECG signals.

## Models

1. **Convolutional Neural Network (CNN)**  
   This model is used for binary classification of heartbeats to identify anomalies. It is trained on normal data and classifies each heartbeat as either normal or abnormal.

2. **LSTM-based Autoencoder**  
   Used for anomaly detection in time-series data. The model is trained on normal data, and when anomalies appear, the reconstruction error increases, signaling potential deviations.
