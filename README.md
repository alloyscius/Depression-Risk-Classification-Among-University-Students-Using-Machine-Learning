# Depression-Risk-Classification-Among-University-Students-Using-Machine-Learning

This project develops and evaluates machine learning and neural network models to predict depression risk based on demographic, academic, lifestyle, and psychological factors. In addition to performance comparison, the study emphasises **model transparency** by applying **SHAP (SHapley Additive exPlanations)** to explain key risk factors influencing model predictions.

---

## 📌 Project Objectives

- Develop a neural network model for predicting depression risk to support social sustainability and mental health well-being
- Assess whether ensemble learning models improve prediction performance
- Enhance model transparency using SHAP to explain influential features contributing to depression risk

---

## 🧠 Models Implemented

The following models are trained and evaluated:

### Neural Networks
- **MLP (ReLU activation)**
- **MLP (tanh activation)**
- **MLP (sigmoid activation)**

### Tree-Based Models
- **Random Forest**
- **XGBoost**

### Ensemble Model
- **Stacking Ensemble**
  - Base learners: Random Forest + XGBoost
  - Meta-learner: Logistic Regression

---

```
## 📂 Project Structure

├── data/
│ └── student_depression_dataset_cleaned.csv
│
│ ├── 01_preprocessing.ipynb
│ ├── 02_model_training_and_evaluation.ipynb
│ └── 03_shap_explainability.ipynb
│
├── models/
│ ├── mlp_relu_model.joblib
│ ├── mlp_tanh_model.joblib
│ ├── mlp_sigmoid_model.joblib
│ ├── rf_model.joblib
│ ├── xgb_model.joblib
│ └── stacking_model.joblib
│
├── data/
│ └── student_depression_dataset_cleaned.csv

```
---
## 🔗 Dataset Source

The dataset used in this project is publicly available on Kaggle:

👉 **Student Depression Dataset**
https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset

This dataset was downloaded and then preprocessed for this study. All original attributes, data collection authorship, and licensing are preserved as per the source.

---
