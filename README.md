# Breast Cancer Prediction using Neural Networks

## 📌 Overview
This project implements a **binary classification model** to predict whether a tumor is **Malignant** or **Benign** using a **Neural Network** built with **TensorFlow** and **Keras**. The dataset is preprocessed, standardized, and trained on a deep learning model for accurate predictions.

---

## 📊 Dataset
The dataset (`breast_cancer.csv`) contains numerical features related to **tumor characteristics**.

### 🎯 Target Variable (`label`):
- `0` → **Malignant (cancerous)**  
- `1` → **Benign (non-cancerous)**  

---

## 🏗 Model Architecture
- **Input Layer:** `30 features`
- **Hidden Layers:**  
  - `Dense(32, activation='relu')`
  - `Dense(16, activation='relu')`
- **Output Layer:** `Dense(1, activation='sigmoid')` *(for binary classification)*
- **Loss Function:** `binary_crossentropy`
- **Optimizer:** `Adam`
- **Metrics:** `Accuracy`, `AUC`

---
# Breast Cancer Prediction

## 2️⃣ Run the Model
To run the breast cancer prediction model, execute the following command in your terminal:

```bash
python breast_cancer_prediction.py


