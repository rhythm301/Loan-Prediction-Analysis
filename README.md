# Loan-Prediction-Analysis
## Overview
This project implements a machine learning system for predicting loan approval status based on applicant information. The system uses multiple classification algorithms to evaluate loan applications and predict whether they should be approved or denied based on various features like income, education, employment status, and other relevant factors.

## Technical Implementation
### Data Preprocessing
- Missing value handling using mode imputation
- Label encoding for categorical variables
- Feature scaling using StandardScaler
- Train-test split with 80-20 ratio
- Data transformation and cleanup for numerical features

### Machine Learning Models Implemented
- Decision Tree Classifier
- Gaussian Naive Bayes
- Random Forest Classifier
- Logistic Regression

### Visualization Components
- Distribution plots for loan amounts and applicant income
- Relationship analysis between different features
- Faceted plots showing income distribution by education and gender/marital status
- Confusion matrix visualization for model evaluation

### Model Performance
The system implements multiple models with the following accuracy scores:
- Decision Tree: ~87%
- Naive Bayes: ~82%
- Random Forest: ~87%
- Logistic Regression: ~82%

## Data Insights

- The dataset shows clear patterns in loan approval rates based on education level and income
- Graduate applicants with higher income levels show higher approval rates
- Credit history plays a significant role in loan approval
- There are notable differences in income distribution patterns across different demographic groups
