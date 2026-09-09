# 🩺 Diabetes Prediction System

A machine learning based healthcare project that predicts whether a
patient is classified as Diabetic or Non-Diabetic based on medical
and health-related information.

## 📌 Project Overview

Diabetes is a common healthcare condition that can lead to serious
health complications if not identified early.

This project uses machine learning techniques to analyze patient
health data and predict diabetes classification.

## 🎯 Objectives

- Analyze the diabetes dataset.
- Clean and preprocess the data.
- Perform Exploratory Data Analysis (EDA).
- Train Logistic Regression and Random Forest models.
- Compare model performance.
- Evaluate the final model using classification metrics.
- Identify important features using Random Forest.
- Predict diabetes classification for new patient data.

## 📊 Dataset

The project uses the Pima Indians Diabetes Dataset obtained from Kaggle.

The dataset contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

### Target

- `0` → Non-Diabetic
- `1` → Diabetic

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## 🤖 Machine Learning Models

### Logistic Regression

Used as a baseline classification model.

### Random Forest

Used as the main prediction model.

## 📈 Model Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 70.78% |
| Random Forest | 77.92% |
| Tuned Random Forest | 74.03% |

### Final Model

Random Forest was selected as the final model because it achieved the
highest test accuracy.

**Random Forest Accuracy:** 77.92%

**ROC-AUC Score:** 0.8192

## ⭐ Feature Importance

The Random Forest model identified Glucose as the most important
feature among the input features in the trained model.

Other important features included:

- BMI
- DiabetesPedigreeFunction
- Age
- Insulin
- BloodPressure

## 🔮 Prediction

The system accepts patient information such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

and predicts:

```text
Diabetic
or
Non-Diabetic
