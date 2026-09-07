# 🩺 Diabetes Prediction Using Deep Learning and Machine Learning

An end-to-end machine learning project that predicts diabetes using an Artificial Neural Network (ANN) implemented with PyTorch and compares its performance against traditional machine learning models.

The project focuses on building a complete binary classification pipeline, from exploratory data analysis and preprocessing to neural network training, model evaluation, hyperparameter tuning, threshold optimization, and reproducible inference.

---

## 📌 Project Overview

The primary objective of this project was to gain practical experience with the complete Artificial Neural Network workflow using PyTorch.

Rather than evaluating the ANN in isolation, its performance was compared with multiple traditional machine learning models. The best-performing model was further optimized and evaluated.

The project covers:

- Exploratory Data Analysis (EDA)
- Train, validation, and test data splitting
- Feature scaling
- PyTorch Dataset and DataLoader
- Artificial Neural Network development
- Model training and validation
- Model checkpointing
- Early stopping
- Performance evaluation
- Machine learning baseline comparison
- Random Forest hyperparameter tuning
- Classification threshold optimization
- Feature importance analysis
- Permutation importance
- Model persistence and reproducible inference

---

# 📊 Dataset

The dataset contains medical and demographic information used to predict whether a patient has diabetes.

### Input Features

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | Serum insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes hereditary likelihood indicator |
| Age | Age of the patient |

### Target Variable

| Value | Class |
|---|---|
| 0 | No Diabetes |
| 1 | Diabetes |

---

# 🔄 Project Workflow

```text
Data Understanding
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Train / Validation / Test Split
        │
        ▼
Feature Scaling
        │
        ▼
ANN Development (PyTorch)
        │
        ▼
Model Training & Validation
        │
        ├── Model Checkpointing
        └── Early Stopping
        │
        ▼
ANN Evaluation
        │
        ▼
Baseline Model Comparison
        │
        ▼
Random Forest Hyperparameter Tuning
        │
        ▼
Threshold Optimization
        │
        ▼
Feature Importance Analysis
        │
        ▼
Model Saving & Reproducible Inference