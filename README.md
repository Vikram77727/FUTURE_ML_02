# 🚨 Bank Customer Churn Forecasting Dashboard  

This project was completed as part of my **Machine Learning Internship**.  
The aim was to build a **predictive system** that can identify customers who are at risk of leaving the bank, so the business can act early with **customer retention strategies**.  

---

## 📌 Project Summary  
- Cleaned and explored the **Bank Churn dataset** to understand customer demographics and behavior.  
- Designed new features such as **age groups, salary-to-balance ratio, and credit-age interactions**.  
- Trained and tested multiple ML models: **Logistic Regression, Random Forest, and XGBoost**.  
- Compared model performance using **Accuracy, Precision, Recall, F1-score, and ROC-AUC**.  
- Exported churn predictions and feature importance data to CSV for visualization.  
- Built an **interactive Power BI dashboard** to highlight churn trends and model results.  

---

## 📂 Main Features  
✅ Predicts churn probability for every customer  

✅ Highlights most important features driving churn  

✅ Visualization of churn distribution and confusion matrix  

✅ Dashboard filters for **country, age bin, credit card status, active membership**  

✅ Side-by-side comparison of models with evaluation metrics  

---

## 🛠️ Tools & Tech  
- **Python** → preprocessing, feature engineering, model training  
- **Libraries** → Pandas, NumPy, Scikit-learn, XGBoost  
- **EDA** → Matplotlib & Seaborn  
- **Power BI** → dashboard for insights and storytelling  

---

## 📊 Dataset  
Used the **Bank Customer Churn dataset** with details of 10,000 customers.  

**Important fields include:**  
- `Geography` → Country of customer  
- `Gender` → Male/Female  
- `Age` → Customer age  
- `CreditScore`, `Balance`, `Tenure`, `NumOfProducts`, `EstimatedSalary`  
- `IsActiveMember`, `HasCrCard` → Service-related indicators  
- `Exited` → Target variable (1 = churned, 0 = retained)  

📂 [Dataset on Kaggle](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers)  

---

## 🤖 Model Evaluation  

| Model               | Accuracy | Precision | Recall  | F1-Score | ROC-AUC |
|----------------------|----------|-----------|---------|----------|---------|
| Logistic Regression  | 0.816    | 0.628     | 0.236   | 0.343    | 0.787   |
| Random Forest        | 0.862    | 0.781     | 0.447   | 0.569    | 0.849   |
| XGBoost              | 0.852    | 0.691     | 0.489   | 0.573    | 0.829   |

📌 **Random Forest** gave the highest accuracy.  
📌 **XGBoost** offered stronger recall and balanced results.  
📌 Logistic Regression was used as a baseline.  

---

## 📈 Dashboard in Power BI  
<img width="1382" height="781" alt="Screenshot 2025-09-04 184856" src="https://github.com/user-attachments/assets/fe14c631-1bb6-49c0-adf0-84e5a7b68922" />


🔗 [Download Dashboard File](https://github.com/Vikram77727/FUTURE_ML_02/blob/d24f810a8ce25ce892fb36599f7db697d16fe153/Ml_Task_2.pbix)

---

## ⚡ How to Run  

### Step 1: Train Models in Python  
- Execute [`ml_task_2.py`] → it preprocesses data, trains models, evaluates, and saves outputs.  
- Generated files:  
  - `customer_churn_insights.csv` → customer churn predictions  
  - `feature_importance_random_forest.csv`  
  - `feature_importance_xgboost.csv`  
  - `feature_importance_logistic_regression.csv`  

### Step 2: Open Dashboard in Power BI  
- Launch Power BI Desktop → open [`ML_Task_2.pbix`]

---

## 📜 Key Takeaways  
This project shows how **machine learning** and **business intelligence tools** can be combined to:  
- Predict churn risk with high accuracy  
- Pinpoint major factors influencing churn  
- Provide actionable insights to improve **customer retention**  

🏆 This was delivered as **Task 2** of my Machine Learning Internship, focusing on **classification, model evaluation, and dashboard reporting**.  
