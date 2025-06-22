# Predicting_customer_churn_telecommunication
# Predicting Customer Churn in Telecommunications

## 📌 Introduction

Customer churn—when subscribers discontinue their services—is a major challenge for telecom companies looking to remain competitive in a rapidly changing market. With evolving technology and rising customer expectations, being able to **predict and reduce churn** is crucial for maintaining long-term growth and profitability.

Churn prediction uses **data analytics** and **machine learning techniques** to identify customers who are likely to leave. By analyzing churn-related factors, telecom providers can take proactive steps to retain customers, enhance satisfaction, and strengthen their business strategies.

![Churn Overview](https://github.com/MdSaifurRahman/Predicting-customer-churn-in-telecommunications./assets/100013081/50365edf-84bc-4afd-88c9-568a7317828e)

---

## 📊 Dataset Overview

**Source**: Kaggle — [Telecom Customer Churn Dataset](https://www.kaggle.com)

This dataset includes customer data from a telecommunications provider, capturing various features such as:

- **Customer Status**: Whether the customer has churned (`Churn` column — target variable)
- **Services Subscribed**: Phone service, multiple lines, internet service, online security, online backup, device protection, tech support, streaming services (TV and movies)
- **Account Information**: Tenure, contract type, payment method, billing preference, monthly and total charges
- **Demographics**: Gender, age group, marital status (partners), and dependents

The dataset contains:
- **7043 rows** representing individual customers  
- **21 columns** representing customer attributes and services

![Dataset Table 1](https://github.com/MdSaifurRahman/Predicting-customer-churn-in-telecommunications./assets/100013081/6b1ff09b-83f1-4d7d-8c22-aa22def50b1d)
![Dataset Table 2](https://github.com/MdSaifurRahman/Predicting-customer-churn-in-telecommunications./assets/100013081/1244d202-7006-4031-bb9a-0afbf2af2fd9)

---

## 🤖 Machine Learning Models & Results

Several machine learning algorithms were implemented and evaluated based on their performance in predicting customer churn. Below are the models used along with their accuracy scores:

| Algorithm              | Accuracy |
|------------------------|----------|
| Decision Tree          | 74%      |
| Random Forest          | 80%      |
| Naive Bayes            | 69%      |

The **Random Forest** classifier delivered the highest accuracy, making it the most effective model for this dataset in our analysis.

---

## 🔍 Conclusion

With accurate churn prediction models, telecom providers can identify at-risk customers early and implement retention measures. This project demonstrates how machine learning can transform raw customer data into actionable insights, helping businesses reduce churn and improve customer engagement.

---

> 📌 *Feel free to fork this repository and explore the code further! If you'd like to see the notebooks, visualizations, or add new models, pull requests are welcome!*
