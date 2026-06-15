# AI-Predictive-Maintenance-System

## Overview

The AI Predictive Maintenance System is an Industry 4.0 inspired project that leverages Machine Learning and Explainable Artificial Intelligence (XAI) to predict the health status of industrial equipment. The system analyzes machine operating parameters such as temperature and vibration levels and classifies machine conditions into Healthy, Warning, or Failure categories.

This project demonstrates how Artificial Intelligence can be used to reduce unplanned downtime, improve maintenance efficiency, and enhance industrial productivity through data-driven decision-making.

---

## Problem Statement

Unexpected machine failures in industries lead to:

* Production downtime
* Increased maintenance costs
* Reduced operational efficiency
* Safety risks
* Revenue losses

Traditional maintenance approaches are often reactive and unable to predict failures before they occur.

This project aims to develop an intelligent predictive maintenance system capable of identifying potential failures before they happen.

---

## Objectives

* Monitor machine operating conditions.
* Analyze temperature and vibration data.
* Predict machine health status using Machine Learning.
* Provide maintenance recommendations.
* Visualize system performance through graphs and dashboards.
* Implement Explainable AI techniques to increase model transparency.

---

## Technologies Used

### Programming Language

* Python

### Machine Learning

* Scikit-Learn
* Random Forest Classifier

### Data Processing

* Pandas
* NumPy

### Data Visualization

* Matplotlib

### Explainable AI

* SHAP (SHapley Additive Explanations)

### Dashboard

* Gradio

### Development Environment

* Google Colab
* Jupyter Notebook

---

## Dataset

The project uses machine condition monitoring data containing:

* Temperature
* Vibration
* Machine Status

### Status Classes

| Class   | Description                      |
| ------- | -------------------------------- |
| Healthy | Normal machine operation         |
| Warning | Early signs of abnormal behavior |
| Failure | High risk of machine breakdown   |

---

## Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Selection
4. Train-Test Split
5. Model Training
6. Prediction
7. Model Evaluation
8. Explainable AI Analysis
9. Dashboard Deployment

---

## Model Used

### Random Forest Classifier

Reasons for selection:

* High accuracy
* Handles non-linear relationships
* Robust against overfitting
* Suitable for industrial datasets
* Provides feature importance analysis

---

## Explainable AI (SHAP)

SHAP is integrated to explain machine learning decisions.

Benefits:

* Improves transparency
* Increases trust in predictions
* Identifies influential features
* Supports industrial decision-making

Example:

Prediction: Failure

Reason:

* Temperature contributed 82%
* Vibration contributed 18%

---

## Dashboard Features

The Gradio Dashboard provides:

* Machine Health Prediction
* Failure Probability Analysis
* Temperature Monitoring
* Vibration Monitoring
* AI-Based Recommendations
* User-Friendly Interface

---

## Performance Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Generated Visualizations

* Machine Health Distribution
* Temperature Distribution
* Vibration Distribution
* Feature Importance Graph
* Confusion Matrix
* Failure Probability Graph
* SHAP Explainability Plot
* Temperature vs Vibration Scatter Plot
* Correlation Matrix

---

## Industrial Applications

This system can be applied in:

* Manufacturing Industries
* Smart Factories
* Industrial Automation Systems
* Automotive Production Plants
* Power Generation Facilities
* Robotics and Automation Systems
* Industry 4.0 Environments

---

## Future Scope

* Real-Time Sensor Integration
* IoT-Based Monitoring
* ESP32 Data Acquisition
* Cloud Connectivity
* Mobile Application Development
* Deep Learning Models
* Multi-Machine Monitoring
* Predictive Maintenance at Enterprise Scale

---

## Project Outcome

This project demonstrates the integration of:

* Artificial Intelligence
* Machine Learning
* Explainable AI
* Industrial Automation
* Data Analytics
* Industry 4.0 Concepts

The developed system successfully predicts machine conditions and provides actionable maintenance recommendations, helping industries move from reactive maintenance to predictive maintenance strategies.

---

## Author

Srujan V

AI and Robotics Automation Engineering

Dayananda Sagar University

