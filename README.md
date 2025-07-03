# Cardiovascular Disease Prediction using Random Forest Classifier

## Project Overview

This project aims to predict the presence of **cardiovascular disease (heart disease)** using machine learning techniques. We utilize a **Random Forest Classifier** to build a predictive model based on patient data, which includes medical measurements, examination results, and lifestyle information.

---

## Dataset Description

The dataset contains **three types of input features:**

- **Objective Features:** Factual and measurable information.
- **Examination Features:** Results from medical examinations.
- **Subjective Features:** Lifestyle information provided by the patient.

### Features Used:
| Feature | Type | Description |
|---------|------|-------------|
| Age | Objective | Age in days |
| Height | Objective | Height in cm |
| Weight | Objective | Weight in kg |
| Gender | Objective | Categorical (encoded) |
| Systolic Blood Pressure | Examination | ap_hi |
| Diastolic Blood Pressure | Examination | ap_lo |
| Cholesterol Level | Examination | 1: Normal, 2: Above Normal, 3: Well Above Normal |
| Glucose Level | Examination | 1: Normal, 2: Above Normal, 3: Well Above Normal |
| Smoking | Subjective | Binary (1: Smokes, 0: Does not smoke) |
| Alcohol Intake | Subjective | Binary (1: Consumes alcohol, 0: Does not consume alcohol) |
| Physical Activity | Subjective | Binary (1: Physically active, 0: Not physically active) |

### Target Variable:
| Feature | Description |
|---------|-------------|
| Cardio | Presence (1) or absence (0) of cardiovascular disease |

---

## Model: Random Forest Classifier

We use the **Random Forest Classifier**, a widely used ensemble learning method that combines multiple decision trees to improve prediction accuracy and control overfitting. 

### Why Random Forest?
- Can handle large datasets and mixed data types.
- Reduces the risk of overfitting by averaging multiple decision trees.
- Can provide **feature importance**, helping us understand which factors most contribute to heart disease.

---

## Project Objectives
- **Data Preprocessing:** Clean the data, handle missing values, encode categorical variables, and scale features if necessary.
- **Model Training:** Train a Random Forest Classifier on the dataset.
- **Model Evaluation:** Evaluate the model using metrics such as:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- **Feature Importance:** Identify the most significant risk factors for cardiovascular disease.

---
