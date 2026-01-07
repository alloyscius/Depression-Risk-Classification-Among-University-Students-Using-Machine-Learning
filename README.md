# Depression-Risk-Classification-Among-University-Students-Using-Machine-Learning

Depression among university students has raised concern as it affects student’s studies, well-being and long-term mental health. This issue relates to the Sustainable Development Goal 3 that focuses on good health and well-being. This study uses machine learning to identify depression risk through analyzing mental health data using neural network and compare with ensemble models to see if predictions can be improved. Shapley Additive explanation (SHAP) is also used to understand the key factors influencing model’s decision and results show that neural network has competitive results compared to ensemble model. However, Neural Network provides more efficient and practical solution due to its simpler model architecture and lower computational complexity which demonstrate the potential of neural network in depression risk decision support system. SHAP has also identified suicidal thoughts, academic pressure, and financial stress as the top 3 influential factor towards the prediction outcome. Overall, this study shows the potential of utilizing machine learning-based decision support system to monitor student’s mental health, detect symptoms earlier, and plans early intervention for students in higher education settings.

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
