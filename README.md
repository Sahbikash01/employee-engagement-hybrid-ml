# employee-engagement-hybrid-ml
# 🚀 Enhancing Employee Engagement Using Hybrid Random Forest and XGBoost

## 📄 Brief One Line Summary
A machine learning–based employee engagement prediction system using a hybrid ensemble of Random Forest and XGBoost to analyze workplace factors and provide actionable improvement suggestions.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Dataset Description](#dataset-description)
- [Features Used](#features-used)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [System Architecture](#system-architecture)
- [Methodology](#methodology)
- [Models Implemented](#models-implemented)
- [Model Evaluation](#model-evaluation)
- [Results & Analysis](#results--analysis)
- [Feature Importance](#feature-importance)
- [User Input Prediction](#user-input-prediction)
- [Engagement Improvement Suggestions](#engagement-improvement-suggestions)
- [Visualizations](#visualizations)
- [How to Run This Project](#how-to-run-this-project)
- [Limitations](#limitations)
- [Future Work](#future-work)
- [Conclusion](#conclusion)
- [Team Members](#team-members)
- [Author & Contact](#author--contact)

---

## Overview

Employee engagement plays a critical role in organizational productivity, retention, and performance—especially in logistics and operations-driven industries.  
This project uses **machine learning ensemble techniques** to predict employee engagement levels based on workplace, performance, and personal factors.

A **Hybrid Voting Classifier** combining **Random Forest** and **XGBoost** is implemented to achieve high accuracy and reliability.

---

## Problem Statement

Traditional employee engagement assessment methods are often subjective, time-consuming, and inconsistent.  
There is a need for a **data-driven, scalable, and intelligent system** that can:

- Predict engagement levels accurately  
- Identify key influencing factors  
- Provide actionable improvement recommendations  

---

## Objectives

- Predict employee engagement (High / Low) using ML
- Combine multiple models for better performance
- Handle class imbalance using SMOTE
- Analyze feature importance
- Provide suggestions to improve engagement

---

## Dataset Description

- **Type:** Synthetic dataset (industry-inspired)
- **Records:** 3000 employees
- **Domain:** Logistics & Operations
- **Target Variable:** Engagement (Binary)

---

## Features Used

- Age  
- Department  
- Job Role  
- Work Hours per Week  
- Remote Work Availability  
- Training Opportunities  
- Career Progression  
- Feedback Frequency  
- Leadership Support  
- Work-Life Balance  
- Salary  
- Delivery Success Rate  
- Warehouse Hours  

---

## Tools & Technologies

- **Programming Language:** Python  
- **Libraries:**  
  - Pandas, NumPy  
  - Scikit-learn  
  - XGBoost  
  - Imbalanced-learn (SMOTE)  
  - Matplotlib, Seaborn  
- **Modeling Techniques:**  
  - Ensemble Learning  
  - Supervised Machine Learning  

---

## Project Structure
```
employee-engagement-hybrid-ml/
│
├── data/
│   └── synthetic_employee_data.csv      # Generated employee dataset (optional)
│
├── src/
│   ├── employee_engagement.py            # Main ML pipeline & prediction script
│   ├── preprocessing.py                 # Data preprocessing & feature scaling
│   ├── model_training.py                # Random Forest, XGBoost & Hybrid models
│   └── evaluation.py                    # Model evaluation & metrics
│
├── results/
│   ├── confusion_matrix.png              # Confusion matrix visualization
│   ├── roc_curve.png                     # ROC curve comparison
│   ├── accuracy_comparison.png           # Model accuracy bar plot
│   └── feature_importance.png            # Feature importance plot
│
├── requirements.txt                      # Project dependencies
├── README.md                             # Project documentation
└── .gitignore                            # Ignored files & folders
```

---

## System Architecture

1. Data Generation  
2. Data Preprocessing  
3. Feature Encoding & Scaling  
4. Class Balancing (SMOTE)  
5. Model Training  
6. Model Evaluation  
7. User Input Prediction  
8. Recommendation System  

---

## Methodology

- Label Encoding for categorical variables
- StandardScaler for numerical features
- SMOTE to balance engagement classes
- Train-test split (80:20)
- Soft voting ensemble for final prediction

---

## Models Implemented

### 🔹 Random Forest Classifier
- Handles non-linearity
- Provides feature importance
- Strong baseline performance

### 🔹 XGBoost Classifier
- Gradient boosting approach
- Fast and efficient
- Reduces overfitting

### 🔹 Hybrid Voting Classifier
- Combines RF + XGBoost
- Soft voting with optimized weights
- Best overall accuracy

---

## Model Evaluation

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Curve

---

## Results & Analysis

| Model | Accuracy |
|------|---------|
| Random Forest | 97.58% |
| XGBoost | 97.10% |
| Hybrid Model | **97.75%** |

✅ The hybrid model achieved the **highest accuracy and balanced performance**.

---

## Feature Importance

Top contributing features:
- Leadership Support  
- Work-Life Balance  
- Training Opportunities  
- Career Progression  
- Delivery Success Rate  

This helps HR teams focus on **high-impact engagement drivers**.

---

## User Input Prediction

The system allows real-time prediction using manual employee inputs such as:
- Role
- Work hours
- Salary
- Support level
- Work-life balance

Output:
- Engagement Level: **High / Low**

---

## Engagement Improvement Suggestions

If engagement is predicted as **Low**, the system suggests:
- More training programs
- Clear career growth paths
- Better leadership support
- Flexible working hours
- Remote work options

---

## Visualizations

- Confusion Matrix
- ROC Curve comparison
- Accuracy bar chart
- Feature importance plot

These visual insights improve **interpretability and trust**.

---

## How to Run This Project

1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/employee-engagement-hybrid-ml.git
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Project
python employee_engagement.py
 4️⃣ Enter Employee Details
Follow on-screen prompts for prediction.```
---
## ⚠️ Limitations

- Uses synthetic data  
- Binary engagement classification (High / Low)  
- Industry-specific assumptions  

---

## 🚀 Future Work

- Use real organizational datasets  
- Deploy the system as a web application  
- Integrate Explainable AI techniques (SHAP / LIME)  
- Extend to multi-class engagement levels  
- Develop an interactive HR dashboard  

---

## 🏁 Conclusion

This project demonstrates how **hybrid ensemble learning** can effectively predict employee engagement with high accuracy.  
It provides both **predictive insights** and **actionable recommendations**, making it highly valuable for **HR analytics and organizational decision-making**.

---

## 👥 Team Members

- **Bikash Sah** – Machine Learning, Model Development, Analysis  
- **Member 2** – Data Processing  
- **Member 3** – Research & Documentation  
- **Member 4** – Visualization & Testing  
