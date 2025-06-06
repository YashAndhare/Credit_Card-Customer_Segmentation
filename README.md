# 💳 Credit Card Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project aims to segment credit card customers based on their spending behavior and interactions with the bank using the **K-Means clustering algorithm**. The segmentation helps the bank understand different customer groups, enabling **personalized marketing** strategies and **enhanced service delivery**.

---

## 🏢 Business Context

AllLife Bank is looking to expand its credit card customer base. Their market research team found:
- Market penetration can be improved through **targeted marketing**.
- Customers perceive the bank’s **support services negatively**.

---

## 🎯 Objective

To identify **distinct customer segments** using clustering, based on:
- Spending patterns
- Service interaction behavior  
The insights will help:
- Launch **personalized campaigns**
- Improve **customer service models**
- Drive **strategic decision-making**

---

## 📁 Dataset

The dataset contains various features representing customer financial and behavioral data.

### 📊 Feature Columns

- Sl_No: Primary key of the records
- Customer Key: Customer identification number
- Average Credit Limit: Average credit limit of each customer for all credit cards
- Total credit cards: Total number of credit cards possessed by the customer
- Total visits bank: Total number of Visits that customer made (yearly) personally to the bank
- Total visits online: Total number of visits or online logins made by the customer (yearly)
- Total calls made: Total number of calls made by the customer to the bank or its customer service department (yearly)

## 🛠️ Operations Performed

### 📥 Data Loading

- Loaded dataset using `pandas` in a Jupyter Notebook

### 📊 Exploratory Data Analysis (EDA)

- Checked for nulls and duplicates
- Scaled features using `StandardScaler`
- Analyzed distributions and outliers

### 📌 Clustering Process

- Applied **K-Means Clustering** for unsupervised segmentation
- Used the **Elbow Method** to find the optimal number of clusters (k)
  
---

## 📈 Key Insights

- Customers with **higher credit limits** and **fewer bank visits** formed a unique segment, indicating high-value customers who prefer digital channels.
- Customers with **frequent customer service calls** and **low online activity** indicated a segment needing better support education or services.
- Some clusters had **moderate usage across all channels**, indicating balanced engagement.

---

## 📊 Model Outcome

- Successfully segmented customers into **3 distinct groups**
- Provided actionable insights for:
  - **Personalized marketing**
  - **Service improvement**
  - **Customer prioritization**

---

## ✅ Conclusion

This K-Means clustering model helped identify **behavioral segments** among credit card customers. These segments can guide:
- **Targeted retention strategies**
- **Better service frameworks**
- **Upsell opportunities** for premium services

The model offers a **scalable solution** to monitor and manage customer types as the bank grows.
