# Customer Churn Prediction

## Introduction
Customer churn—when customers stop using a company’s products or services—is a major challenge for businesses. High churn can lead to substantial revenue loss, making it crucial to identify and retain at-risk customers.  
This project focuses on building **machine learning models** to predict customer churn, enabling businesses to take proactive actions before customers leave.  

The workflow involved:  
1. **Data Preprocessing** – Cleaning and transforming raw data for analysis.  
2. **Exploratory Data Analysis (EDA)** – Identifying patterns and relationships in customer behavior.  
3. **Feature Engineering** – Creating meaningful new features and preparing data for modeling.  
4. **Modeling** – Applying multiple machine learning algorithms to predict churn.  
5. **Model Evaluation** – Comparing models using performance metrics.  
6. **Insights & Interpretation** – Understanding the main factors driving churn.  

---

## Techniques Used

### 1. Exploratory Data Analysis (EDA)
- **Visualizations**: Histograms, bar plots, and correlation heatmaps were used to detect churn patterns.  
- **Key Observations**:  
  - **Contract Type**: Customers with *month-to-month* contracts had much higher churn rates.  
  - **Monthly Charges**: High monthly charges were strongly linked to churn.  
  - **Tenure**: Newer customers were more likely to leave.  

---

### 2. Feature Engineering
- **Tenure Categories** – Grouped customers into categories (e.g., *new*, *medium*, *loyal*) to capture loyalty effects.  
- **One-Hot Encoding** – Converted categorical features like contract type, payment method, and internet service into numeric format.  
- **Scaling** – Normalized numerical features (e.g., monthly charges) to improve model accuracy.  

---

### 3. Modeling
The following machine learning models were implemented and compared:  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  

---

## Key Insights
1. **Contract Type** – *Month-to-month* customers were far more likely to churn compared to long-term contract holders.  
2. **Monthly Charges** – Customers with higher charges had a greater tendency to leave.  
3. **Tenure** – Newer customers churned more frequently than long-standing customers.  
4. **Paperless Billing** – Slightly higher churn rates were seen among customers with paperless billing, possibly due to reduced personal interaction.  

---


