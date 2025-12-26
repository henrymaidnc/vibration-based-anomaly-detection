# Vibration-Based Anomaly Detection using Time-Series Analysis

## 1. Overview
Industrial machines such as rotating bearings generate vibration signals that
contain rich information about their health condition. Abnormal vibration patterns
often indicate early-stage faults that cannot be easily observed in the time domain.

This project investigates vibration-based anomaly detection using time-series
analysis and unsupervised learning methods, with a focus on frequency-domain
representations and deep autoencoder models.

---

## 2. Motivation
Predictive maintenance aims to detect machine degradation before catastrophic
failure occurs. Traditional rule-based monitoring methods rely heavily on domain
expert knowledge and fixed thresholds, which often fail to generalize across
machines and operating conditions.

By combining signal processing techniques (FFT, STFT) with data-driven
time-series models, this project explores a scalable and model-agnostic
approach to anomaly detection for industrial vibration data.

---

## 3. Problem Definition
Given a vibration time-series collected from machine-mounted sensors,
the objective is to:

- Learn normal operating patterns from historical data
- Detect abnormal behavior without requiring fault labels
- Identify temporal regions where anomalies emerge

This problem is formulated as an **unsupervised anomaly detection task**
on time-series data.

---

## 4. Dataset
- **Dataset**: IMS Bearing Dataset
- **Source**: NASA Prognostics Center of Excellence
- **Data Type**: High-frequency vibration signals
- **Sensors**: Accelerometers mounted on rotating bearings

The dataset contains run-to-failure experiments, making it suitable for
condition monitoring and degradation analysis.

---

## 5. Methodology (High-Level)
The proposed pipeline consists of the following stages:

1. Raw vibration signal preprocessing
2. Sliding window segmentation
3. Frequency-domain transformation (FFT / STFT)
4. Unsupervised anomaly detection using autoencoder models
5. Anomaly scoring based on reconstruction error

Detailed implementation will be provided in the notebooks.

---

## 6. Project Structure
```text
vibration-based-anomaly-detection/
│
├── data/ # Raw and processed vibration data
├── notebooks/ # Exploratory analysis and experiments
├── src/ # Reusable preprocessing and model code
├── results/ # Figures and evaluation outputs
└── docs/ # Daily Research Todo
└── README.md
```

---

## 7. Status
🚧 Work in progress  
This repository is actively updated with daily research commits.

---

## 8. Author
This project is developed as part of a research portfolio for MSc scholarship
applications in Machine Learning / Artificial Intelligence.
