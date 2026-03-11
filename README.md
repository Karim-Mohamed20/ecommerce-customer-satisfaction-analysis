## 🛍️ E-Commerce Customer Satisfaction Analysis (Big Data Project)

This project analyzes and predicts **customer satisfaction in an e-commerce platform** using the **Olist Brazilian E-Commerce dataset**.  
The goal is to explore customer behavior, discover patterns in purchases, and build machine learning models that predict **customer review scores**.

The project applies **data cleaning, exploratory data analysis, feature engineering, association rule mining, and machine learning models using PySpark**.

---

## 📊 Dataset

Dataset used: **Olist E-Commerce Dataset**

Real e-commerce data from Brazil including:

- Customers
- Orders
- Products
- Payments
- Reviews
- Sellers
- Delivery information

Kaggle dataset:  
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

![](image.png)

---

## 🎯 Project Objective

To **analyze customer satisfaction and predict review scores** based on:

- Customer purchasing behavior
- Delivery time
- Payment methods
- Product information

---

## ⚙️ Project Pipeline

The project follows a full **data science pipeline**:

### 1️⃣ Data Cleaning
- Remove unnecessary columns
- Handle missing values
- Merge related columns

### 2️⃣ Data Exploration
- Analyze distributions and trends
- Generate visualizations to understand customer behavior

### 3️⃣ Data Preprocessing
- Feature engineering
- Prepare dataset for machine learning models

### 4️⃣ Big Data Processing with PySpark
- Create Spark session
- Train multiple ML models

### 5️⃣ Association Rule Mining
Discover relationships between:
- Payment methods
- Delivery performance
- Customer satisfaction

---

## 📈 Exploratory Data Analysis

Key insights explored in the project:

- Distribution of review scores
- Most common payment methods
- Top customer states
- Top seller states
- Payment value vs review score
- Product price vs satisfaction
- Freight value vs satisfaction
- Delivery time vs review score
- Product category distribution
- Top selling product categories

Correlation analysis was also performed to understand relationships between features.

---

## 🔎 Association Rules

Association rule mining was used to discover interesting relationships between features.

Examples:

- **Excellent review → Credit Card payment**
- **Credit Card → Excellent review**
- **Excellent review → Very small payment value**
- **On-time delivery → Excellent review**
- **Fast delivery → Excellent review**
- **SP state → Excellent review**

These rules help understand **factors influencing customer satisfaction**.

---

## 🤖 Machine Learning Models

Several models were trained to predict **customer review scores**.

| Model | Accuracy | F1 Score |
|------|------|------|
| Random Forest | 59.9% | 47.3 |
| Logistic Regression | 59.7% | 47.4 |
| Decision Tree | 60% | 47.3 |
| Naïve Bayes | 54% | 47 |

---

## ⚠️ Unsuccessful Trials

- SVM model took very long time to train on the dataset.
- Applying PCA for feature reduction resulted in lower accuracy.

---

## 🚀 Future Work

Possible improvements for the project:

- Better feature engineering
- Hyperparameter tuning
- Trying advanced models
- Improving class balance
- Increasing model accuracy

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- PySpark
- Scikit-learn
- Jupyter Notebook
