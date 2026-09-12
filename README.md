# Customer Churn Prediction Using Machine Learning

## 📌 Project Overview

Customer churn is a major challenge for telecom companies. Losing customers can reduce revenue and increase the cost of acquiring new customers.

This project uses Machine Learning to predict whether a telecom customer is likely to churn based on customer demographics, services, contract details, tenure, and account information.

The project compares **Logistic Regression** and **Random Forest** models and evaluates their performance using Accuracy, Recall, and ROC-AUC.

---

## 🎯 Objective

The main objectives of this project are:

- Predict whether a customer is likely to leave the telecom service.
- Identify important factors that influence customer churn.
- Compare different Machine Learning classification models.
- Provide insights that can help telecom companies improve customer retention.

---

## 📊 Dataset

The project uses the **IBM Telco Customer Churn Dataset**.

The dataset contains information about telecom customers, including:

- Customer demographics
- Tenure
- Internet and phone services
- Contract type
- Payment method
- Monthly charges
- Total charges
- Churn status

After data cleaning, **7,021 customer records** were used for analysis.

### Target Variable

- `No` → Customer stays
- `Yes` → Customer churns

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

---

## 🤖 Machine Learning Models

Two classification algorithms were implemented:

### 1. Logistic Regression

Used as the primary classification model for predicting customer churn.

### 2. Random Forest

Used as a comparison model and to identify important features affecting customer churn.

---

## 📈 Model Performance

| Model | Accuracy | Recall | ROC-AUC |
|---|---:|---:|---:|
| Logistic Regression | 80.28% | 52.42% | 84.03% |
| Random Forest | 77.79% | 44.35% | 81.31% |

### Best Model

**Logistic Regression** performed better overall, achieving:

- **80.28% Accuracy**
- **52.42% Recall**
- **84.03% ROC-AUC**

---

## 🔍 Key Factors Affecting Churn

The Random Forest model was used to identify important factors related to customer churn.

Some of the important factors include:

- Total Charges
- Tenure
- Monthly Charges
- Month-to-month Contract
- Online Security
- Fiber Optic Internet Service
- Electronic Check Payment
- Tech Support
- Senior Citizen Status
- Online Backup

---

## 📊 Exploratory Data Analysis

The project includes visual analysis of:

- Customer Churn Distribution
- Churn by Contract Type
- Churn by Internet Service
- Monthly Charges vs Churn
- Tenure vs Churn

These visualizations help understand customer behavior and identify patterns associated with churn.

---

## 🔄 Project Workflow

```text
Dataset Collection
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Preparation
       ↓
Train-Test Split
       ↓
Data Preprocessing
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Feature Importance Analysis
       ↓
Final Model Selection
```
---

## 💡 Key Insights

The analysis shows that customer churn is influenced by factors such as:

- Contract type
- Customer tenure
- Monthly charges
- Internet service
- Online security and technical support
- Payment method

Customers with shorter tenure and month-to-month contracts are particularly important groups to monitor for potential churn.

---

## 🚀 Future Improvements

The project can be further improved by:

- Hyperparameter tuning
- Handling class imbalance using techniques such as SMOTE
- Testing additional Machine Learning algorithms
- Optimizing the prediction threshold
- Deploying the model as a web application
- Adding real-time customer churn prediction

---

## 📁 Project Files

- `Customer_Churn_Prediction_ML.ipynb` — Complete Machine Learning notebook
- `README.md` — Project documentation

---

## 👩‍💻 Author

**Zoya**

Engineering Student | Machine Learning Enthusiast
