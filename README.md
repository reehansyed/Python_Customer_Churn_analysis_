# Python_Customer_Churn_analysis
![view python file](https://github.com/reehansyed/Python_Customer_Churn_analysis_/blob/main/TCA.ipynb)
## Table of Contents
- Project Overview
- Dataset Description
- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Key Insights
- Conclusion
- Requirements
- Usage
- ## 📊 Project Overview
This project aims to perform an in-depth analysis of customer churn in a telecom company using a comprehensive dataset that includes various customer attributes. By leveraging data exploration and visualization techniques, the goal is to identify and understand the key factors that contribute to customer churn. The analysis covers different aspects such as customer demographics, service usage, and payment methods, with the objective of uncovering patterns and correlations that can help the company mitigate churn and improve customer retention strategies.
## 📋 Dataset Description
The dataset consists of 7043 rows and 21 columns with the following features:

- **customerID:** Unique identifier for each customer.
- **gender:** Gender of the customer (Male/Female).
- **SeniorCitizen:** Whether the customer is a senior citizen (1 for yes, 0 for no).
- **Partner:** Whether the customer has a partner (Yes/No).
- **Dependents:** Whether the customer has dependents (Yes/No).
- **tenure:** Number of months the customer has been with the company.
- **PhoneService:** Whether the customer has phone service (Yes/No).
- **MultipleLines:** Whether the customer has multiple phone lines (Yes/No).
- **InternetService:** Type of internet service (DSL/Fiber optic/No).
- **OnlineSecurity:** Whether the customer has online security (Yes/No).
- **OnlineBackup:** Whether the customer has online backup (Yes/No).
- **DeviceProtection:** Whether the customer has device protection (Yes/No).
- **TechSupport:** Whether the customer has tech support (Yes/No).
- **StreamingTV:** Whether the customer has streaming TV (Yes/No).
- **StreamingMovies:** Whether the customer has streaming movies (Yes/No).
- **Contract:** Type of contract (Month-to-month/One year/Two year).
- **PaperlessBilling:** Whether the customer has paperless billing (Yes/No).
- **PaymentMethod:** Payment method used (Electronic check/Mailed check/Bank transfer/credit card).
- **MonthlyCharges:** The monthly charge the customer pays.
- **TotalCharges:** The total amount the customer has paid.
- **Churn:** Whether the customer has churned (Yes/No).
## 🧹 Data Cleaning and Preprocessing
- Missing Values: There are no missing values in the dataset.
- Data Type Conversion: The TotalCharges column was initially stored as a string with some blank spaces, which were replaced with zeros and converted to float.
- Feature Transformation: The SeniorCitizen column, which contains binary values (0 and 1), was transformed into categorical values ("No" and "Yes") for easier interpretation.
##  🔍 Exploratory Data Analysis
### 1. Churn Distribution:

- A count plot and pie chart were used to show the distribution of churned vs non-churned customers.
- 26.54% of the customers have churned.
### 2. Churn by Gender:

- A count plot visualized churn distribution by gender, revealing that churn rates are fairly similar between males and females.
### 3.Churn by Senior Citizen Status:

- Senior citizens have a higher churn rate compared to non-senior citizens, as shown by a stacked bar chart.
### 4. Churn by Tenure:

- A histogram shows that customers who have been with the company for a longer period are less likely to churn, while those with shorter tenures are more likely to churn.
### 5. Churn by Contract Type:

- Customers with month-to-month contracts have a higher churn rate compared to those with one-year or two-year contracts.
### 6. Churn by Service Usage:

- A series of count plots showed that customers who use services like PhoneService, InternetService, and OnlineSecurity are less likely to churn, while customers who do not use these services tend to churn more.
### 7. Churn by Payment Method:

- Customers using electronic check as a payment method are more likely to churn compared to other payment methods.  

