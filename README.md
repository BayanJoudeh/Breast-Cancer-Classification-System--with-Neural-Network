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

## ⚙️ Setup & Execution

### 1️⃣ Install Dependencies
```bash
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn
2️⃣ Run the Model
bash
Copy
Edit
python breast_cancer_prediction.py
3️⃣ Model Evaluation
✅ Test Accuracy & AUC are printed after training.
✅ A confusion matrix can be added for deeper insights.

4️⃣ Making Predictions
🔹 Input a new sample tumor feature vector
🔹 The model predicts whether the tumor is Malignant or Benign

