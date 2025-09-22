# Acute Myocardial Infarction (AMI) Prediction using Machine Learning

## 📖 Project Overview
This project focuses on predicting *Acute Myocardial Infarction (AMI)* (commonly known as heart attack) using patient clinical and biomarker data. The goal is to build a machine learning model that can assist in *early detection and diagnosis*, potentially supporting healthcare professionals in decision-making.


## 📊 Dataset
- The dataset contains patient information such as *age, gender, heart rate, blood sugar, troponin levels, CK-MB*, and final diagnosis (AMI present/absent).
- Target variable: *Result* (0 = Negative, 1 = Positive).
- Source: [Mendeley Dataset / Kaggle / (specify actual source you used)].


## ⚙ Methodology
1. *Data Preprocessing*
   - Handled categorical and numerical variables
   - Visualized distributions (histograms, countplots)
   - Converted target values into binary format (0/1)

2. *Model Training*
   - Logistic Regression
   - Random Forest
   - XGBoost

3. *Evaluation Metrics*
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix
   - ROC Curve & AUC Score


## 📈 Results
- *Logistic Regression: Accuracy = 79%
- *Random Forest: Accuracy = 99%
- *XGBoost: Accuracy = 98%

Confusion matrices and ROC curve comparisons were used to evaluate performance.  
📌 Random Forest achieved the *best overall results* with 99% accuracy.


## 🚀 Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
