# CodeAlpha Task 4 - Disease Prediction  

This repository contains my implementation of **Task 4: Disease Prediction from Medical Data** for the Code Alpha Internship program.  

## 📌 Project Overview  
The goal of this project is to predict whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)** using patient medical data and machine learning classification algorithms.  

## 📂 Dataset  
- **Name:** Breast Cancer Wisconsin (Diagnostic)  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))  
- **Features:** Measurements such as mean radius, mean texture, smoothness, compactness, concavity, etc.  
- **Target:** Binary classification → Malignant / Benign.  

## ⚙️ Methodology  
1. **Data Preprocessing**  
   - Checked for null/missing values.  
   - Applied **StandardScaler** for feature scaling.  
   - Performed **train-test split** for evaluation.  

2. **Model Building**  
   - Implemented multiple ML classifiers:  
     - Logistic Regression  
     - Support Vector Machine (SVM)  
     - Random Forest  
     - XGBoost  

3. **Evaluation**  
   - Metrics used: Accuracy, Precision, Recall, F1-score, Confusion Matrix.  
   - Compared model performances to select the best classifier.  

## 🛠️ Tools & Libraries  
- Python  
- pandas, numpy → Data handling  
- scikit-learn → ML models and metrics  
- matplotlib, seaborn → Visualization  
- xgboost → Advanced boosting algorithm  

## 📊 Results  
- All models performed well, but **Random Forest and XGBoost** achieved the best accuracy.  
- Visualizations confirmed strong separation between malignant and benign classes.  

## 🚀 How to Run  
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/CodeAlpha-Task4-Disease-Prediction.git

📌 Internship Note
This project is part of the Code Alpha Internship – Task 4 and demonstrates the use of machine learning algorithms for predicting diseases using structured medical datasets.
