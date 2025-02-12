# AI_for_ECG

**Course Work 2023 - 2024**

A project focused on analyzing Holter monitoring data using machine learning methods to detect anomalies related to ST-segment changes in ECG signals.

## About the Project

The goal of this project is to develop a system for analyzing ECG data to detect abnormal conditions such as myocardial infarction or ischemia by identifying changes in the ST-segment. The system utilizes machine learning to process 24-hour ECG recordings and detect anomalous heartbeats. You can explore the heart rate calculation, spectrogram generation, and model training in the provided Jupyter notebooks.

## Models

1. **Convolutional Neural Network (CNN)**  
   This model is used for binary classification of heartbeats to identify anomalies. It is trained on normal data and classifies each heartbeat as either normal or abnormal.

2. **LSTM-based Autoencoder**  
   Used for anomaly detection in time-series data. The model is trained on normal data, and when anomalies appear, the reconstruction error increases, signaling potential deviations.

## Notebooks

Explore the following Jupyter notebooks for different stages of the project:
- **`heart_rate.ipynb`**: A notebook for calculating heart rate variability from ECG data.
- **`spectrogram.ipynb`**: A notebook for creating spectrograms of Holter monitoring data.
- **`models/cnn_model.ipynb`**: A notebook for training the Convolutional Neural Network (CNN) model for heartbeat anomaly detection.
- **`models/lstm_autoencoder.ipynb`**: A notebook for training the LSTM-based autoencoder model for anomaly detection in time-series ECG data.

