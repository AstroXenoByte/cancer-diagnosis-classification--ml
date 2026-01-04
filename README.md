# Breast Cancer Diagnosis Prediction using Machine Learning

## Overview
This project focuses on predicting whether a breast tumor is **malignant (M)** or **benign (B)** using machine learning classification models.  
The dataset consists of medical diagnostic measurements derived from breast cancer biopsies.

Multiple models were trained, evaluated, and saved for future use.

---

## Dataset
- Source: Breast Cancer Diagnostic Dataset
- Total Samples: 569
- Features: 30 numerical features
- Target:
  - `1` → Malignant (M)
  - `0` → Benign (B)

Unnecessary columns such as `id` and `Unnamed: 32` were removed during preprocessing.

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

## Machine Learning Models
The following models were trained and evaluated:

- **Logistic Regression**
- **Random Forest Classifier**
- **XGBoost Classifier**

### Model Accuracy
- Logistic Regression: **97.36%**
- Random Forest Classifier: **95.61%**
- XGBoost Classifier: **95.61%**

---

## Workflow
1. Load and explore the dataset
2. Clean and preprocess data
3. Encode target labels
4. Feature scaling using StandardScaler
5. Train multiple ML models
6. Evaluate model performance
7. Save trained models and accuracy results

---

## Saved Files
- `logistic_model.pkl`
- `rf_model.pkl`
- `xgb_model.pkl`
- `model_accuracies.txt`

These files allow the models to be reused without retraining.

---

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
