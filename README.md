# 🏠Customer Churn Prediction Project

**Objective:** Predict Customer Churn(yes/no) using various target variables.

**Model:** Random forest classifier model

**Includes:** Data Cleaning, Preprocessing, Visualizations, Model Building & Evaluation

 ### Overview
 Customer churn, or customer attrition, refers to when a customer ceases their relationship
 with a company or service provider. In today's highly competitive business environment,
 retaining customers is a critical factor for long-term success. Predicting customer churn can
 help organizations take proactive steps to retain customers, thus minimizing revenue loss.
 This project aims to build a machine learning model that can predict whether a customer will
 churn based on their demographic, account, and service-related data

 ### Problem Statement
 The goal of this project is to develop a classification model that predicts whether a customer
 will churn. Using demographic data (such as gender, senior citizen status, and tenure), along
 with information about the services they use (such as internet service, phone service, and
 online security), we will attempt to build a model that helps the company identify customers
 who are at a high risk of churning.
 By predicting customer churn, the company can proactively design retention strategies to
 keep these customers, thereby improving customer satisfaction and reducing financial loss.

 ## Steps done:
 1. Data preprocessing and Exploration
 2. Data Cleaning
 3. Feature Scaling
 4. Train test split
 5. Outliers detection
 6. Customer churn
 7. Model Building

 8. Model Evaluation

Accuracy: 0.7810945273631841
Precision: 0.613013698630137
Recall: 0.4786096256684492
F1 Score: 0.5375375375375375
![download](https://github.com/user-attachments/assets/b9376645-b710-4c54-aaf0-9d81201fa4b0)
![download](https://github.com/user-attachments/assets/08b7c28f-3a73-437e-a4ac-a44bf8d3f0ee)

### 📌 Confusion Matrix Explanation
- **True Positives (TP)** → Customers who actually churned and were correctly predicted as "Churn."
- **True Negatives (TN)** → Customers who did not churn and were correctly predicted as "No Churn."
- **False Positives (FP)** (Type I Error) → Customers who did not churn but were incorrectly predicted as "Churn."  
  - This could lead to unnecessary retention efforts.
- **False Negatives (FN)** (Type II Error) → Customers who churned but were incorrectly predicted as "No Churn."  
  - This is **more costly** because the company **misses** saving a customer at risk.
  
#### **📊 Business Impact of Errors**
- **High FP (Type I Errors)** → Wastes resources trying to retain non-churning customers.  
- **High FN (Type II Errors)** → **Dangerous for business** because we fail to retain customers who will actually leave.  
- **Goal:** Minimize **False Negatives** to improve customer retention strategies.

