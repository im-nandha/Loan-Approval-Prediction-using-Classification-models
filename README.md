# Loan-Approval-Prediction-using-Classification-models
Project Overview
This project focuses on predicting loan approval status based on a dataset of applicant details. By applying classification models, the goal is to accurately classify whether a loan will be approved or not. The project employs three machine learning algorithms:

1. Decision Tree
2. Random Forest
3. Logistic Regression
The models are evaluated to determine their accuracy, precision, recall, and other relevant metrics.

# Dataset
The dataset includes details such as applicant income, credit history, loan amount, property area, and more. Each record has a target variable indicating loan approval status (Approved or Not Approved). The dataset has been preprocessed to handle missing values and encode categorical variables.

# Tools and Technologies
programming language : Python

Libraries Used:
1. Scikit-learn (for model implementation)
2. Pandas and NumPy (for data manipulation)
3. Matplotlib and Seaborn (for data visualization)

# Methodology
# 1. Data Preprocessing:
  Handled missing values by using mean/mode imputation.
  Converted categorical variables into numerical form using one-hot encoding or label encoding.
  Standardized/normalized numerical features.

# 2. Model Building:
  Decision Tree: Built using Gini impurity as the criterion for splitting.
  Random Forest: An ensemble technique combining multiple decision trees for better accuracy.
  Logistic Regression: A statistical model to predict probabilities and classify outcomes.
 
# 3. Model Evaluation:
  Used metrics such as Accuracy, Precision, Recall, F1-score, and ROC-AUC.
  Compared the performance of all three models.
