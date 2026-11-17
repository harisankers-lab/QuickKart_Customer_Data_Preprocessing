# QuickKart Customer Data Preprocessing

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) and preprocessing on a customer dataset from QuickKart. The objective is to clean and prepare raw customer data for machine learning applications.

## Dataset Description
The dataset contains customer demographic information, membership details, payment preferences and purchasing behaviour.

**Key Features:**
- Customer_ID
- Age
- Gender
- City
- Membership
- Payment_Mode
- Monthly_Income
- Orders_Last_Year
- Avg_Order_Value
- Total_Spent

## Preprocessing Workflow

### 1. Exploratory Data Analysis (EDA)
- Dataset structure and statistical summaries
- Missing value identification
- Duplicate detection
- Categorical value inspection
- Distribution analysis using histograms
- Skewness analysis
- Outlier detection using boxplots and IQR

### 2. Data Cleaning
- Standardization of inconsistent categorical values
- Removal of duplicate records
- Missing value imputation using median and mode
- Handling invalid age values
- Outlier treatment using IQR-based capping

### 3. Categorical Encoding
- Label Encoding: Gender
- Ordinal Encoding: Membership
- One-Hot Encoding: City and Payment_Mode

### 4. Feature Scaling
- StandardScaler applied to numerical features
- Train-test split (80:20)
- Stratified sampling to maintain target class distribution
- Fitting the scaler on training data and transforming testing data

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Target Variable
Gender is selected as the target variable for a potential multiclass classification task.

## Project Status
Data preprocessing completed. The dataset is prepared for subsequent machine learning applications.

---

**Note:** This repository focuses on exploratory data analysis and data preprocessing. Model development and evaluation are outside the current scope.
