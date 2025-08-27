Chronic Kidney Disease Prediction

This repository contains the implementation of the MSc Data Science project:
Comparative Analysis of Logistic Regression, Decision Tree, and Support Vector Machine for Chronic Kidney Disease Prediction

The project applies supervised machine learning techniques on clinical and laboratory datasets to predict Chronic Kidney Disease (CKD).

📌 Project Overview

Objective: Develop a reliable and interpretable machine learning pipeline for early CKD detection.

Dataset: Chronic Kidney Disease Dataset (Kaggle)

Techniques Used:

Exploratory Data Analysis (EDA)

Data Cleaning (imputation, outlier removal, balancing)

Feature Engineering & One-Hot Encoding

Model Training & Hyperparameter Tuning

⚙️ Models Implemented

Logistic Regression (LR) – Baseline interpretable model

Decision Tree (DT) – Non-linear, interpretable rules

Support Vector Machine (SVM) – Tuned with RBF & Linear kernels

📊 Results Summary
Model	Accuracy	Precision	Recall	F1-score
Logistic Regression	98.33%	0.97	1.00	0.98
Decision Tree (Tuned)	98.33%	0.97	1.00	0.98
SVM (Tuned)	98.33%	0.97	1.00	0.98

✅ All tuned models achieved 98.33% accuracy and perfect recall (1.00) ensuring no CKD-positive case was missed.

📂 Repository Structure
├── data/                  # Dataset (from Kaggle)
├── notebooks/             # Jupyter notebooks for EDA & model training
├── scripts/               # Python scripts for preprocessing & modeling
├── results/               # Saved confusion matrices, plots, and metrics
├── README.md              # Project documentation

🚀 Installation & Usage

Clone the repository:

git clone https://github.com/Abbasshakoor70/Chronic-kidney-disease-prediction.git
cd Chronic-kidney-disease-prediction


Install dependencies:

pip install -r requirements.txt


Run the notebook or scripts:

jupyter notebook notebooks/CKD_Prediction.ipynb

📌 Key Findings

CKD can be reliably classified with simple interpretable algorithms.

Important predictors: blood urea, serum creatinine, hemoglobin, urine measurements (specific gravity & albumin).

Balanced dataset & hyperparameter tuning significantly improved performance, especially for SVM.

📖 Citation

If you use this project, please cite:
Muhammad Abbas Shakoor (2025). Comparative Analysis of Logistic Regression, Decision Tree, and Support Vector Machine for Chronic Kidney Disease Prediction. MSc Data Science Project, University of Hertfordshire.

👨‍💻 Author

Name: Muhammad Abbas Shakoor

GitHub: Abbasshakoor70
