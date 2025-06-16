# Data Engineering for IoT - Modern Car Project

## Overview

This project showcases a full-stack data engineering pipeline tailored for IoT data, culminating in a predictive analytics system for a **modern connected car**. It demonstrates how raw data from sensors can be ingested, transformed, analyzed, visualized, and used for predictive modeling. The project covers the end-to-end lifecycle of data, using multiple data formats and tools commonly used in the industry.

## Features

- **Data Formats**: The project handles and processes multiple common IoT data formats:
  - `CSV` for structured tabular sensor data
  - `JSON` for semi-structured log and telemetry data
  - `XML` for metadata and device configurations

- **Data Ingestion**:
  - Collected data from simulated IoT sensors representing different car components
  - Ingested into a data lake using batch and stream processing techniques
  - Technologies used: Python, Kafka (optional), local filesystem, and mock APIs

- **Data Transformation**:
  - Data cleaning, schema harmonization, and normalization
  - Parsing and converting between CSV, JSON, and XML formats
  - Used `Pandas` and `PySpark` for transformation at scale

- **Data Processing**:
  - ETL pipeline built to preprocess sensor data
  - Extracted features like speed, fuel efficiency, tire pressure trends, engine temperature over time
  - Anomaly detection and alert generation logic implemented

- **Data Analytics**:
  - Exploratory Data Analysis (EDA) on historical IoT data
  - Generated insights about vehicle usage patterns, driver behavior, and potential faults
  - Visual summaries and statistics to support decision-making

- **Visualization with Grafana**:
  - Live dashboards created using Grafana
  - Real-time monitoring of IoT metrics (e.g., RPM, oil levels, GPS)
  - Alerts for anomalies like overheating, sudden acceleration, or abnormal tire pressure

- **Predictive Modeling**:
  - Machine learning models trained to predict:
    - Component failures
    - Remaining useful life (RUL) of parts
    - Fuel efficiency based on driving behavior
  - Models built using `scikit-learn`, `XGBoost`, and `TensorFlow`
  - Performance evaluated with metrics like RMSE, accuracy, and precision-recall

## Final Project: Smart Car IoT System

The final integration demonstrates a **smart connected car** ecosystem. It simulates:

- Live data feed from vehicle sensors
- A robust pipeline for processing and analyzing that data in real time
- Predictive alerts for maintenance and performance optimization
- Interactive dashboards for real-time monitoring

This project exemplifies a scalable, extensible, and efficient IoT data engineering solution for automotive applications.

## Technologies Used

- Python, Pandas, PySpark
- Kafka, MQTT (optional setup)
- Grafana, Inf
