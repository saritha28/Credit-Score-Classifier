# Credit Score Classifier

## Overview
This project involves building a credit score classifier based on a dataset comprising 28 columns and 42040 records. The dataset includes various features such as age, income, credit history, outstanding debts, credit utilization ratio, and more. The objective is to predict credit scores based on these features.

## Dataset Information
- **Columns**: 28 columns including ID, Customer_ID, Month, Name, Age, SSN, Occupation, Annual_Income, Monthly_Inhand_Salary, Num_Bank_Accounts, Num_Credit_Card, Interest_Rate, Num_of_Loan, Type_of_Loan, Delay_from_due_date, Num_of_Delayed_Payment, Changed_Credit_Limit, Num_Credit_Inquiries, Credit_Mix, Outstanding_Debt, Credit_Utilization_Ratio, Credit_History_Age, Payment_of_Min_Amount, Total_EMI_per_month, Amount_invested_monthly, Payment_Behaviour, Monthly_Balance, and Credit_Score.
- **Records**: 42040 records with various credit-related information.

## Model and Accuracy
- **Classifier Used**: Decision Tree Classifier (Entropy), Logistic Regression, Random Forest Classifier (Gini criterion).
- **Accuracy**:
  - Random Forest Classifier: Achieved 72% accuracy.
  - Decision Tree Classifier: Achieved 69% accuracy.
  - Logistic Regression: Achieved 56% accuracy.

## Methodology
- **Data Preprocessing**: Handling missing values, converting categorical variables, and feature engineering.
- **Model Training**: Employed Decision Tree, Logistic Regression, and Random Forest algorithms.
- **Model Evaluation**: Assessed model performance based on accuracy metrics.

## Usage
- **Data Exploration**: Analyze the dataset to understand features and their relevance.
- **Model Building**: Use the provided dataset to build and train credit score prediction models.
- **Model Selection**: Compare and evaluate the performance of Decision Tree, Logistic Regression, and Random Forest classifiers.
- **Predictions**: Make predictions on new data to classify credit scores.

## Limitations and Future Improvements
- The accuracy of the models could be further improved with additional feature engineering and selection.
- Exploring other classification algorithms might yield better performance.

## Author
- Saritha B
- https://www.linkedin.com/in/saritha-bathini

## Conclusion
- RandomForest Classifier is the best model with 72% accuracy
