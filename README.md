Credit Card Approval Prediction -- Phase 1 (EDA)
📌 Project Overview
Credit card companies must evaluate applicants carefully to minimize
defaults and financial risk. This project analyzes customer demographic,
financial, and credit-related information to understand patterns that
influence credit approval decisions.
This repository covers Phase 1: Exploratory Data Analysis (EDA) of a
credit card approval prediction system.
🚀 Objective
To explore and analyze the dataset to identify trends, patterns, and
risk indicators that help predict whether an applicant is eligible for a
credit card.
📊 Dataset Summary
⦁	Total Rows: 36,457\
⦁	Total Columns: 21\
⦁	Numerical Features: 12\
⦁	Categorical Features: 9
Data includes:
⦁	Demographics (age, gender, family status)
⦁	Financial info (income, credit amount)
⦁	Employment details
⦁	Asset ownership
⦁	Repayment & credit history indicators
🎯 Problem Statements
1️⃣ Predicting Default
Problem: How can we predict whether a customer may default on credit
obligations?  
Goal: Build a classification model to differentiate defaulters vs
non-defaulters.
2️⃣ Understanding Influencing Factors
Problem: Which demographic & financial factors influence credit
default?  
Goal: Identify key predictors such as income, age, employment
stability.
3️⃣ Impact of Credit History
Problem: How does repayment history affect loan/credit approval?  
Goal: Analyze correlation between credit history and default
likelihood.
4️⃣ Customer Segmentation
Problem: Can segmentation improve approval accuracy?  
Goal: Cluster customers into risk-based groups for smarter
decision-making.
5️⃣ Data Quality Challenges
Problem: Missing values, imbalance & outliers affect model
accuracy.  
Goal: Apply preprocessing techniques for clean & balanced
model-ready data.
🔍 Key Insights From Phase 1 EDA
⦁	Applicants with stable jobs and long work experience show lower
default risk.\
⦁	Income distribution is highly skewed---lower-income groups
default more.\
⦁	The target variable is imbalanced (more non-defaulters).\
⦁	Categorical indicators such as FLAG_MOBIL, FLAG_OWN_CAR,
FLAG_OWN_REALTY are structured and useful.\
⦁	Numerical columns like AMT_INCOME_TOTAL and CREDIT_AMOUNT
contain significant outliers.\
⦁	Payment history indicators (e.g., STATUS, WORST_STATUS_NUM)
strongly influence default predictions.\
⦁	Dataset contains a healthy mix of numerical & categorical features
for modeling.
📚 Phase 1 Conclusion
⦁	Conducted detailed EDA to understand the data structure &
relationships.\
⦁	Identified key predictors of default risk such as income,
employment stability & repayment history.\
⦁	Detected missing values, outliers & imbalance to be handled in Phase
2.\
⦁	Prepared the foundation for Preprocessing → Modeling →
Evaluation.
