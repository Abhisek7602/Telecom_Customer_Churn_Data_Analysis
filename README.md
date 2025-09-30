# Telecom_Customer_Churn_Data_Analysis

## Brief Summary
A data-driven analysis factors contributing to customer churn in a telecom dataset and The main objective is to identify these high-risk customer segments to inform targeted retention strategies.

---

## Table of Contents
1. [Overview](#overview)  
2. [Problem Statement](#problem-statement)  
3. [Dataset](#dataset)  
4. [Tools and Technologies](#tools-and-technologies)  
5. [Methods](#methods)  
6. [Key Insights](#key-insights)  
7. [Results and Conclusion](#results-and-conclusion)  
8. [Author and Contact](#author-and-contact)

---

## Overview
The analysis focuses on understanding the characteristics of customers who churn (cancel their service) versus those who do not. It explores the relationship between churn and various customer attributes, including demographics, contract details, services subscribed to, billing preferences, and payment methods. The ultimate goal is to identify key factors contributing to churn to help in retention efforts.

---

## Problem Statement
The core problem is to identify and quantify the factors that significantly influence a customer's decision to churn from the service. This involves determining which customer segments, contract types, service bundles, and billing/payment methods are most strongly associated with a higher churn rate

---

## Dataset
The dataset appears to be from a telecommunications or streaming service provider and includes features such as:
Target Variable: Churn (Yes/No).
Demographics: Gender, Senior Citizen status.
Contract Details: Tenure (length of service), Contract Type (Month-to-month, One year, Two year).
Services: PhoneService, MultipleLines, InternetService (DSL, Fiber optic), OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies.
Billing/Payment: PaperlessBilling, PaymentMethod (Electronic check, Mailed check, Bank transfer, Credit card).

---

**Target :**  
Our goal is to identify key factors contributing to churn to help in retention efforts.

---

## Tools and Technologies
Programming Language: Python
Data Manipulation/Analysis: Pandas
Visualization Libraries: Matplotlib and/or Seaborn

---

## Methods
The analysis primarily employs Exploratory Data Analysis (EDA) and Univariate/Bivariate Analysis using:
Count Plots: To visualize the distribution of churn across different categories (e.g., services, contract type, gender).
Bar Plots: Similar to count plots, showing the absolute count of churn for various features.
Pie Charts: To display the overall percentage split between churned and non-churned customers.
The method involves visually comparing the ratio or absolute count of 'Yes' (Churn) to 'No' (No Churn) within each category of the independent variables.

---

## Key Insights
The visualizations reveal several critical factors driving churn:
1.Contract Type: Customers on a Month-to-month contract have a vastly higher churn rate (1655 churn vs. 2220 no churn) compared to those with One year (166 2.churn vs. 1307 no churn) or Two year (48 churn vs. 1647 no churn) contracts.
3.Tenure: The churn rate is highest among customers with lower tenure (service length) and decreases significantly as tenure increases.
4Internet Service: Customers with Fiber optic internet service show a high number of churns (1297 churn vs. 1799 no churn) compared to DSL or no internet service.
5.Security & Support: Customers who do not subscribe to value-added security and support services like OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, or StreamingMovies are generally more likely to churn than those who do. For instance, in TechSupport, 'No' has more churn (1446) than 'Yes' (310).
6.Billing & Payment:Paperless Billing: Customers using PaperlessBilling have a significantly higher number of churns (1400 churn vs. 2771 no churn) compared to those who do not (469 churn vs. 2403 no churn).
7.Payment Method: The Electronic check payment method has the highest churn count (1071), indicating a strong association with customer attrition.
Demographics:Senior Citizen: Senior Citizens have a higher propensity to churn (476 churn vs. 666 no churn) relative to non-senior citizens (1393 churn vs. 4506 no churn).
8.Gender: Gender (Female/Male) shows a virtually equal churn count (939 vs. 930), suggesting it is not a significant predictor of churn.

---

## Results and Conclusion
The overall churn rate for the dataset is approximately 26.5% (1869 churn vs. 5174 no churn). The key churn drivers identified are:
1.Contract: Month-to-month contracts are the most vulnerable.
2.Payment: Electronic check users are highly likely to churn.
3.Internet: Customers with Fiber optic service show higher churn.
4.Services: Lack of Online Security and Tech Support services increases churn risk.
5.Customer churn is not random but is strongly correlated with service preferences, contract terms, and billing practices. To effectively reduce churn, the provider should prioritize efforts on customers who are on month-to-month contracts, use Electronic checks, and lack security/support services. Strategies should include incentivizing longer-term contracts, exploring issues with the Fiber optic service and Electronic check payment process, and promoting value-added services like OnlineSecurity and TechSupport to at-risk segments.

---

## Author and Contact
**Author:** Abhisek Nayak 
**Email:** nayakabhisek7602@gmail.com 
**LinkedIn/GitHub:** [www.linkedin.com/in/abhisek-nayak-88054a362]

