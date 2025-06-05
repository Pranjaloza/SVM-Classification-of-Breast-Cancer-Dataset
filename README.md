# SVM-Classification-of-Breast-Cancer-Dataset
This project performs binary classification on the Breast Cancer dataset using Support Vector Machines (SVM) with both linear and non-linear (RBF) kernels.


## 📌 Objectives

- ✅ Load and preprocess a real-world medical dataset.
- ✅ Train SVM classifiers using **linear** and **RBF** kernels.
- ✅ Visualize decision boundaries using **PCA (2D)**.
- ✅ Tune hyperparameters like **C** and **gamma** using **GridSearchCV**.
- ✅ Evaluate model performance using **accuracy**, **confusion matrix**, and **classification report**.
- ✅ Apply **cross-validation** for robust validation.

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn (SVC, PCA, GridSearchCV, metrics)
- Seaborn, Matplotlib

## 📊 Dataset

- **Source**: Breast Cancer Dataset (CSV format)
- Contains features like age, tumor size, shape, and other characteristics.
- Target column indicates if the tumor is **benign (0)** or **malignant (1)**.

---
## 📈 Results Summary

- Both linear and RBF SVMs performed well.
- Best accuracy achieved after **hyperparameter tuning**.
- **PCA-based decision boundary visualization** shows clear class separation in 2D.
- Model evaluation includes confusion matrix and classification report.
