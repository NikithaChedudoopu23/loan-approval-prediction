# 🏦 Loan Approval Prediction

This project builds a **Machine Learning Model** to predict loan approval based on applicant financial history, income, and credit scores. We used **Logistic Regression, Random Forest, XGBoost, and Neural Networks** to improve accuracy and address class imbalance.

## 🎯 Objectives
- **Predict loan approval** based on applicant financial attributes.
- **Address class imbalance** using techniques like SMOTE.
- **Compare model performance** across multiple machine learning algorithms.
- **Interpret feature importance** using SHAP values.

## 📊 Technologies Used
- **Python (Pandas, NumPy, Scikit-Learn, TensorFlow)**
- **Machine Learning Models:** Logistic Regression, Random Forest, XGBoost, Neural Networks
- **Data Preprocessing & Feature Engineering**
- **Class Imbalance Handling:** Oversampling (SMOTE)

## 📂 Dataset
- The dataset was sourced from [Kaggle](https://www.kaggle.com/competitions/playground-series-s4e10/data).
- It contains **58,645 rows** and **13 columns**, including numerical and categorical features.

## 📊 Model Performance
Model                |	Accuracy | Recall (Class 1) |	AUC-ROC  

Logistic Regression	 |   90%	   |        42%	    |      87%

Random Forest	       |  89%	     |       76%	    |      90%

XGBoost	             |   84%	   |         81%	  |      89%

Neural Network	     |   73%	   |         76%	  |       91%

📌 XGBoost achieved the highest overall accuracy, Random Forest achieved the highest AUC-ROC, while Neural Networks performed best in recall.

## 📌 Key Insights

Feature Importance: Loan interest rate, credit history length, and income were the top predictors.

Handling Class Imbalance: Using SMOTE improved recall from 42% (Logistic Regression) to 81% (XGBoost).

Loan Default Patterns: Applicants with short credit histories and high-income-to-loan ratios were more likely to be denied.
