# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is one of the major challenges faced by subscription-based businesses. Losing existing customers impacts revenue and growth.  

This project focuses on analyzing customer behavior and building a Machine Learning model that predicts whether a customer is likely to churn or continue using the service.

The system helps businesses identify high-risk customers early and take necessary retention actions.

---

## 🎯 Objective

- Analyze customer data and identify churn patterns
- Perform data cleaning and preprocessing
- Build a predictive Machine Learning model
- Evaluate model performance using classification metrics
- Deploy the model using an interactive Streamlit web application

---

## 🛠️ Tech Stack Used

### Programming Language
- Python

### Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Streamlit

### Machine Learning
- Logistic Regression

---

## 📂 Project Workflow


Raw Dataset
      |
      ↓
Data Cleaning & Preprocessing
      |
      ↓
Exploratory Data Analysis (EDA)
      |
      ↓
Feature Engineering
      |
      ↓
Train-Test Split
      |
      ↓
Model Training
      |
      ↓
Model Evaluation
      |
      ↓
Streamlit Deployment


---

## 📊 Exploratory Data Analysis

Performed detailed analysis to understand:

- Customer demographic information
- Service usage behavior
- Churn distribution
- Relationship between features and churn
- Important factors affecting customer retention

Visualization techniques were used to discover meaningful business insights.

---

## 🤖 Machine Learning Model

### Model Used:
**Logistic Regression**

Logistic Regression was selected as the classification algorithm to predict customer churn probability.

The model learns patterns from customer information and classifies customers into:

- Churn Customer
- Non-Churn Customer

---

## 📈 Model Performance

| Metric | Score |
|---|---|
| Accuracy | 78% |
| AUC-ROC Score | 0.8155 |
| Precision | 0.5945 |
| Recall | 0.5228 |

The model achieved a good ROC-AUC score, showing its ability to distinguish between churn and non-churn customers.

---

## 🚀 Streamlit Web Application

An interactive Streamlit application was developed where users can:

✔ Enter customer details  
✔ Get churn prediction instantly  
✔ View prediction output through a simple interface  

---

## 📁 Project Structure


Customer-Churn-Analysis/

│

├── dataset/

│   └── Customer data

│

├── model/

│   └── Trained ML model

│

├── app.py

│

├── churn_analysis.ipynb

│

├── requirements.txt

│

└── README.md


---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/SUBIKSHA-37/Customer-Churn-Analysis.git
2. Navigate to Project Folder
cd Customer-Churn-Analysis
3. Install Requirements
pip install -r requirements.txt
4. Run Streamlit App
streamlit run app.py
🔮 Future Improvements
Try advanced algorithms like Random Forest and XGBoost
Improve recall score for churn customers
Hyperparameter tuning
Cloud deployment
Add customer retention recommendations
📌 Key Learnings

Through this project, I gained experience in:

End-to-end Machine Learning workflow
Data preprocessing
Exploratory Data Analysis
Classification model development
Model evaluation techniques
Building ML applications using Streamlit
👩‍💻 Author

Subiksha Lakshmi M

B.Tech Artificial Intelligence & Data Science

GitHub: SUBIKSHA-37
