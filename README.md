# Brain_Tumor_Classification
Passionate about AI and Machine Learning, with experience in data preprocessing, model training, and evaluation. I enjoy applying these skills to solve problems and am currently learning AI research, Python, and data analysis to strengthen my foundation for future projects.

# 🧠 Brain Tumor Classification using Machine Learning

This project implements a **machine learning pipeline** to classify brain tumors based on a dataset of extracted features.  
It uses **Logistic Regression, Random Forest, Support Vector Machines (SVM), and XGBoost** with **hyperparameter tuning** to achieve optimal performance.

---

## 📌 Features of the Project
- **Data Preprocessing**
  - Handles missing values and infinity values.
  - Drops irrelevant columns (e.g., `Image` column if present).
  - Standardizes features using `StandardScaler`.
  - Uses **SMOTE** to handle class imbalance.

- **Model Training**
  - Trains four classifiers:
    - Logistic Regression
    - Random Forest Classifier
    - Support Vector Machine (SVM)
    - XGBoost Classifier
  - Uses **GridSearchCV** for hyperparameter optimization.

- **Evaluation Metrics**
  - Accuracy
  - AUC-ROC score
  - Classification report
  - Confusion matrix heatmaps

- **Feature Importance Analysis**
  - Visualizes top features for **Random Forest** and **XGBoost**.
