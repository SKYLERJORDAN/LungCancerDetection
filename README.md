# Lung Cancer Prediction

A machine learning project aimed at predicting the presence of lung cancer based on patient data. This system could serve as a decision-support tool for early detection and diagnosis of lung cancer.

## 🧠 Overview

The goal of this project is to develop a classifier that can accurately predict whether a patient is likely to have lung cancer based on features like age, smoking habits, chronic diseases, and other clinical indicators.

## 📂 Dataset
- Features: 
  - Age
  - Gender
  - Smoking habits
  - Anxiety
  - Chronic diseases
  - Fatigue, etc.
- Target: Lung Cancer (Yes/No)

## ⚙️ Preprocessing

- Null value handling
- Label encoding / One-hot encoding for categorical features
- Normalization or Standardization
- Train-test split

## 🏗️ Model Architecture

- Built using **scikit-learn**
- Algorithms tested:
  - Logistic Regression
  - Random Forest
  - SVM
  - KNN
- Best performing model: _e.g., Random Forest_

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Curve

## ✅ Results

- Best model accuracy: _e.g., 89%_
- Confusion matrix and classification report are visualized
- ROC curve used to analyze model performance

## 🛠️ Installation

```bash
git clone https://github.com/SKYLERJORDAN/lung-cancer-prediction.git
cd lung-cancer-prediction
pip install -r requirements.txt
