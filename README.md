# Predicting Mortality of Heart Failure Patients

This project aims to build a predictive model for identifying the risk of death in patients suffering from heart failure. Using clinical records and machine learning algorithms, we analyze various patient parameters to determine the likelihood of mortality, which can assist healthcare providers in proactive treatment planning.

## 🩺 Project Overview

The dataset consists of clinical features such as age, blood pressure, ejection fraction, serum creatinine, and other medical indicators. We preprocess the data, perform exploratory data analysis (EDA), and apply classification models to predict whether a patient is likely to die during the follow-up period.

## 📊 Features

- Age of patient
- Anaemia (binary)
- High blood pressure (binary)
- Creatinine phosphokinase levels
- Diabetes (binary)
- Ejection fraction
- Platelets count
- Serum creatinine
- Serum sodium
- Sex
- Smoking
- Time (follow-up period)
- Death event (target)

## 📁 Dataset

- **Source**: UCI Machine Learning Repository  
- **Records**: 299 patient cases  
- **Target variable**: `DEATH_EVENT` (1 = death, 0 = survived)

## ⚙️ Models Used

- **Support Vector Machine (SVM)**
- **Artificial Neural Network (ANN)**
- Others explored: Logistic Regression, Random Forest, etc.

## 📈 Evaluation Metrics

We evaluated models using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC-AUC Curve**

> 🔍 **Best Model:**  
> The Artificial Neural Network outperformed the SVM model with better precision, recall, and F1-score, showing its strength in capturing complex non-linear patterns.

## 🧪 Setup & Run

### Requirements

Install the dependencies with:

```bash
pip install -r requirements.txt
