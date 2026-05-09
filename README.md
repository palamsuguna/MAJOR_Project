# Vital-Signs–Driven Early Warning System Using Survival Models

## 📌 Overview
This project presents a low-cost and interpretable healthcare early-warning system that predicts patient health deterioration using basic vital signs and survival analysis techniques.

The system is specially designed for rural and resource-limited healthcare environments where advanced medical facilities and diagnostic tools are limited. It uses physiological parameters such as heart rate, oxygen saturation, respiratory rate, body temperature, blood pressure, age, and comorbidities to estimate both the risk and timing of patient deterioration.

The proposed model is based on the Cox Proportional Hazards (CoxPH) survival model integrated with a Red-Flag Alert Layer for detecting abnormal health trends and generating early-warning alerts.

---

# 🎯 Objectives
- Predict patient health deterioration at an early stage
- Estimate both risk level and expected deterioration time
- Provide interpretable healthcare predictions
- Support rural and low-resource healthcare systems
- Generate alert notifications for abnormal health conditions

---

# 🚀 Features
- Survival analysis using CoxPH model
- Time-aware risk prediction
- Red-Flag Alert mechanism
- Early detection of patient deterioration
- Lightweight and low-cost system
- Interpretable healthcare predictions
- Trend-based monitoring of patient vitals
- Suitable for rural healthcare environments

---

# 🏥 Input Parameters
The system uses the following patient vital signs and information:

- Heart Rate
- Blood Pressure
- Oxygen Saturation (SpO2)
- Respiratory Rate
- Body Temperature
- Age
- Comorbidities

---

# 🧠 Methodology
1. Data Collection
2. Data Preprocessing
3. Missing Value Handling
4. Feature Engineering
5. Normalization and Scaling
6. Survival Data Structuring
7. CoxPH Model Training
8. Risk Prediction
9. Trend Monitoring
10. Red-Flag Alert Generation

---

# 📊 Dataset Information

## Dataset Used
**MIMIC-IV Clinical Database (Demo Version 2.2)**

## Dataset Details
- 100 Patients
- 275 Hospital Admissions
- 140 ICU Stays
- 668,862 Clinical Events

## Dataset Attributes
- subject_id
- hadm_id
- charttime
- heart_rate
- blood_pressure
- spo2
- respiratory_rate
- temperature
- age
- comorbidities

---

# ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Lifelines
- Survival Analysis
- Cox Proportional Hazards Model

---

# 🚨 Red-Flag Alert System
The Red-Flag Layer detects dangerous health trends such as:

- SpO2 below 90%
- High fever above 38°C
- Rising heart rate
- Increasing respiratory rate
- No recovery trend

The system generates alerts and recommendations for timely medical attention.

---

# 📈 Model Performance
- Concordance Index (C-Index): **0.675**

The model provides moderate predictive performance for ranking patient deterioration risk over time.

---

# ✅ Advantages
- Early risk prediction
- Low-cost healthcare solution
- Interpretable predictions
- Supports healthcare workers
- Time-aware monitoring
- Suitable for rural healthcare systems
- Reduces delayed medical intervention

---

# 🌍 Social Impact
This project helps improve healthcare accessibility in underserved regions by enabling early detection of patient deterioration using affordable medical measurements and intelligent prediction techniques.

---

# 🔮 Future Enhancements
- Wearable device integration
- Mobile healthcare applications
- Real-time IoT monitoring
- Electronic Health Record (EHR) integration
- Advanced AI survival models
- Cloud deployment

---

# 👨‍💻 Authors
- Palam Suguna
- Shaik Meheq Kausar

## Guided By
Dr. Ganji Ramanjaiah

Department of Computer Science & Engineering (Data Science)  
R.V.R. & J.C. College of Engineering (Autonomous)

---
