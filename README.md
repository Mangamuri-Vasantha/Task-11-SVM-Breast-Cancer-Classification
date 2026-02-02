# Task-11-SVM-Breast-Cancer-Classification
# 🧠 SVM – Breast Cancer Classification

This project is part of the **AI & ML Internship – Task 11**, focusing on **Support Vector Machine (SVM)** for binary classification using a breast cancer dataset.

The objective is to classify tumors as **Benign** or **Malignant** and understand kernel-based classification and hyperparameter tuning.

---

## 📌 Task Objectives

- Load and explore the breast cancer dataset
- Preprocess data using feature scaling
- Train SVM models with:
  - Linear Kernel
  - RBF Kernel
- Compare model performance
- Tune hyperparameters using GridSearchCV
- Evaluate model using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC Curve & AUC
- Save the best-performing model

---

## 📂 Dataset

- **Source:** Breast Cancer Dataset (CSV)
- **Target Column:** `diagnosis`
  - `M` → Malignant
  - `B` → Benign
- **Features:** Numerical tumor measurements

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib

---

## 🔄 Workflow

1. Import required libraries  
2. Load and inspect the dataset  
3. Encode target labels  
4. Split data into training and testing sets  
5. Apply `StandardScaler` for feature normalization  
6. Train baseline SVM with **Linear Kernel**  
7. Train SVM with **RBF Kernel**  
8. Tune `C` and `gamma` using **GridSearchCV**  
9. Evaluate best model using classification metrics  
10. Plot **ROC Curve** and compute **AUC score**  
11. Save the trained model pipeline  

---

## 📊 Results & Evaluation

- Linear and RBF kernels were compared
- RBF kernel performed better after hyperparameter tuning
- Model evaluation includes:
  - Confusion Matrix
  - Classification Report
  - ROC Curve
  - AUC Score

---

## 💾 Saved Model

The best-performing model (Scaler + SVM) is saved as:

-svm_breast_cancer_model.pkl
