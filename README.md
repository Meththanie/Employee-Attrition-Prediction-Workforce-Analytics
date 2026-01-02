# Employee Attrition Prediction & Workforce Analytics

## 📌 Project Overview
Employee attrition is a major challenge for organizations, leading to increased hiring costs, reduced productivity, and loss of skilled talent.  
This project uses **machine learning techniques** to analyze workforce data and predict employees who are at risk of leaving an organization.

The study focuses on identifying key factors influencing attrition and building predictive models to support **data-driven HR decision-making**.

---

## 🎯 Objectives
- Analyze employee demographics and job-related factors
- Identify key drivers of employee attrition
- Build and compare machine learning models for attrition prediction
- Improve prediction performance through feature engineering and hyperparameter tuning

---

## 📊 Dataset
- Source: Kaggle – Employee Attrition Uncleaned Dataset  
- Records: **74,610 employees**
- Target Variable:
  - `Attrition` → 0 = Stayed, 1 = Left

### Key Features
- Age, Monthly Income, Years at Company
- Job Role, Gender, Education Level
- Work-Life Balance, Job Satisfaction
- Performance Rating, Promotions
- Remote Work, Company Size

🔗 Dataset link:  
https://www.kaggle.com/datasets/nikhilbhosle/employee-attrition-uncleaned-dataset

---

## 🛠️ Methodology

### 1. Data Preprocessing
- Removed duplicates
- Handled missing values
- Outlier treatment using IQR method
- Dropped irrelevant columns (Employee ID)

### 2. Feature Engineering
- Promotion Rate
- Work-Life Balance Score
- Attrition Risk Score
- Multicollinearity check using VIF

### 3. Exploratory Data Analysis (EDA)
- Attrition by age, gender, job role
- Work-life balance & job satisfaction analysis
- Income vs attrition trends
- Correlation heatmap

---

## 🤖 Machine Learning Models
- Logistic Regression
- Random Forest Classifier

### Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|------|--------|----------|--------|--------|
| Logistic Regression | 68.34% | 68% | 68% | 68% |
| Random Forest (Tuned) | **70.90%** | 71% | 71% | 71% |

- ROC-AUC (Random Forest): **0.79**

---

## 🔧 Model Tuning
- Hyperparameter tuning using `RandomizedSearchCV`
- Best model: **Random Forest**
- Improved stability and non-linear pattern detection

---

## 📈 Key Insights
- Younger employees show higher attrition
- Poor work-life balance significantly increases attrition risk
- Lower income employees are more likely to leave
- Job satisfaction is a strong predictor of retention

---

## 📂 Project Structure
