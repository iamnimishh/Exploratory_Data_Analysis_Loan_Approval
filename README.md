**Loan Approval Dataset Analysis**

This repository contains code and analysis for exploring and predicting loan approval status based on a dataset containing various features related to loan applications.

## Dataset Description

The dataset, stored in the file `loan_approval_dataset.csv`, contains the following columns:

- `loan_id`: Unique identifier for each loan application.
- `no_of_dependents`: Number of dependents of the loan applicant.
- `education`: Education level of the loan applicant (e.g., Graduate, Not Graduate).
- `self_employed`: Whether the applicant is self-employed (Yes or No).
- `income_annum`: Annual income of the loan applicant.
- `loan_amount`: Requested loan amount.
- `loan_term`: Loan term in months.
- `cibil_score`: Credit score of the applicant.
- `residential_assets_value`: Value of residential assets owned by the applicant.
- `commercial_assets_value`: Value of commercial assets owned by the applicant.
- `luxury_assets_value`: Value of luxury assets owned by the applicant.
- `bank_asset_value`: Value of assets held by the applicant in a bank.
- `loan_status`: Target variable - Loan approval status (Approved or Rejected).

## Analysis Overview

The Jupyter Notebook `Loan_Approval_Analysis.ipynb` contains the step-by-step analysis performed on the dataset. The analysis includes:

1. Data Preprocessing:
   - Handling missing values and data cleaning.
   - Encoding categorical variables (education and self_employed) using one-hot encoding.
   - Splitting the dataset into training and testing sets.

2. Exploratory Data Analysis (EDA):
   - Visualizing the distribution of loan approvals based on education level using a stacked bar chart.
   - Calculating summary statistics for numerical features.

3. Machine Learning Models:
   - Applying various machine learning algorithms, such as Logistic Regression, Decision Trees, Random Forest, SVM, and Gradient Boosting (XGBoost).
   - Training and evaluating the models to predict loan approval status.

## Requirements

To run the code, you'll need the following libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost

You can install the required libraries using `pip`:

```
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

## How to Use

1. Clone this repository to your local machine.

2. Make sure you have Python and the required libraries installed.

3. Open and run the Jupyter Notebook `Loan_Approval_Analysis.ipynb` to reproduce the analysis and explore the results.

4. Feel free to modify the notebook or add more analyses as per your requirements.
5. 


