# 🚀 Predictive Maintenance Classification using IBM Watsonx AutoAI

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/IBM-Watsonx-black?style=for-the-badge&logo=ibm">
  <img src="https://img.shields.io/badge/Machine%20Learning-99.5%25%20Accuracy-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

---

## 📌 Project Overview

Industrial machine failures can lead to costly downtime, production delays, and maintenance expenses.

This project leverages **Machine Learning** and **IBM Watsonx AutoAI** to predict different types of machine failures before they occur, enabling organizations to take proactive maintenance actions and improve operational efficiency.

The model analyzes real-time machine sensor and operational data to classify failure categories with high accuracy.

---

## 🎯 Problem Statement

Develop a predictive maintenance model capable of identifying machine failure types using industrial sensor data.

The solution should:

✅ Analyze machine operational parameters

✅ Detect hidden failure patterns

✅ Predict failure categories

✅ Support proactive maintenance planning

✅ Reduce downtime and operational costs

---

## 🏭 Business Impact

Predictive Maintenance helps industries:

* Reduce unexpected machine breakdowns
* Improve equipment reliability
* Minimize maintenance costs
* Increase production uptime
* Enable data-driven maintenance scheduling

---

## 📊 Dataset Information

Dataset: Machine Predictive Maintenance Classification Dataset

The dataset contains machine operating conditions and sensor measurements.

### Features

| Feature             | Description                 |
| ------------------- | --------------------------- |
| Type                | Machine category            |
| Air Temperature     | Ambient air temperature     |
| Process Temperature | Machine process temperature |
| Rotational Speed    | RPM of machine              |
| Torque              | Torque generated            |
| Tool Wear           | Tool wear duration          |
| Machine Failure     | Failure indicator           |

### Target Variable

**Failure Type**

Possible classes:

* No Failure
* Tool Wear Failure
* Heat Dissipation Failure
* Power Failure
* Overstrain Failure
* Random Failure

---

## ⚙️ Technology Stack

### Machine Learning

* IBM Watsonx AutoAI
* Scikit-Learn
* Snap ML
* XGBoost
* LightGBM

### Development

* Python 3.12
* Jupyter Notebook
* IBM Cloud

### Version Control

* Git
* GitHub

---

## 🔍 Machine Learning Workflow

```text
Raw Dataset
     │
     ▼
Data Preprocessing
     │
     ▼
Feature Engineering
     │
     ▼
AutoAI Pipeline Generation
     │
     ▼
Model Training
     │
     ▼
Hyperparameter Optimization
     │
     ▼
Pipeline Evaluation
     │
     ▼
Best Model Selection
     │
     ▼
Failure Type Prediction
```

---

## 🧠 Model Training

IBM Watsonx AutoAI automatically generated and evaluated multiple machine learning pipelines.

Models evaluated include:

* Random Forest
* Snap Random Forest
* XGBoost
* LightGBM
* Ensemble Models

The highest-performing model was selected based on classification accuracy.

---

## 🏆 Results

### Best Model

**Batched Tree Ensemble Classifier**

### Performance Metrics

| Metric              | Value                     |
| ------------------- | ------------------------- |
| Prediction Type     | Multiclass Classification |
| Optimization Metric | Accuracy                  |
| Best Accuracy       | 99.5%                     |
| Holdout Size        | 10%                       |

---

## 📈 Sample Prediction

### Input

```text
Air Temperature: 298 K
Process Temperature: 309 K
Rotational Speed: 1500 RPM
Torque: 42 Nm
Tool Wear: 150 min
```

### Output

```text
Failure Type: Tool Wear Failure

Risk Level: High

Recommended Action:
Replace cutting tool and inspect spindle alignment.
```

---

## 📂 Repository Structure

```text
Predictive-Maintenance-Classification/
│
├── Predictive Maintenance Model.ipynb
│
├── screenshots/
│   ├── leaderboard.png
│   ├── model_pipeline.png
│   └── results.png
│
├── requirements.txt
│
├── LICENSE
│
└── README.md
```

---

## 📸 Project Screenshots

### Best Pipeline

<img width="1852" height="659" alt="Screenshot 2026-06-01 145033" src="https://github.com/user-attachments/assets/6ff1c4ad-8f6e-42f7-ac37-67729a0a4130" />


### Model Results

<img width="1887" height="639" alt="Screenshot 2026-06-01 145158" src="https://github.com/user-attachments/assets/1872c8f3-c18c-47de-87fc-36ca51bd02ce" />

### Model deployed online

<img width="1894" height="811" alt="Screenshot 2026-06-02 081208" src="https://github.com/user-attachments/assets/5861631c-efe0-4cc5-8f84-34eabb0d59c9" />

### API endpoint generated

<img width="1763" height="754" alt="Screenshot 2026-06-02 081722" src="https://github.com/user-attachments/assets/7606aaf2-dcd5-47c1-aefb-b0716d00aed4" />



---

## 🔮 Future Enhancements

* Real-time IoT sensor integration
* Edge deployment
* Predictive maintenance dashboard
* Maintenance recommendation engine
* Cloud deployment API
* Digital twin integration

---

## 👨‍💻 Author

### Aditya Dey

Computer Science & Engineering Student

AI • Machine Learning • Automation • Intelligent Systems
---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

### "Predict failures before they happen — because prevention is cheaper than downtime."
