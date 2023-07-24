**Exploratory Data Analysis: Loan Approval**

This repository contains an exploratory data analysis (EDA) of a loan approval dataset. The primary focus of this analysis is to gain insights into the loan approval process and understand the relationships between different features in the dataset.

## Dataset Description

The dataset, stored in the file `loan_approval_dataset.csv`, comprises the following columns:

- `loan_id`: Unique identifier for each loan application.
- `no_of_dependents`: Number of dependents of the loan applicant.
- `education`: Education level of the loan applicant (e.g., Graduate, Not Graduate).
- `self_employed`: Indicates whether the applicant is self-employed (Yes or No).
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

The Jupyter Notebook `Exploratory_Data_Analysis_Loan_Approval.ipynb` contains the detailed exploratory data analysis on the loan approval dataset. The analysis includes:

1. Data Preprocessing:
   - Handling missing values and data cleaning.
   - Encoding categorical variables (education and self_employed) using one-hot encoding.
   - Splitting the dataset into training and testing sets.

2. Univariate Analysis:
   - Visualizing the distribution of numerical features using histograms and box plots.
   - Analyzing the frequency distribution of categorical variables through bar charts.

3. Bivariate Analysis:
   - Examining the relationship between loan approval status and other features.
   - Identifying correlations and dependencies between different features.

4. Data Visualizations:
   - Creating various plots, such as scatter plots and bar charts, to illustrate patterns and trends.

## Requirements

To execute the code, ensure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn

You can install these libraries using `pip`:

```
pip install pandas numpy matplotlib seaborn
```

## How to Use

1. Clone this repository to your local machine.

2. Ensure you have Python and the required libraries installed.

3. Open and run the Jupyter Notebook `Exploratory_Data_Analysis_Loan_Approval.ipynb` to reproduce the analysis and explore the insights.

4. Feel free to modify the notebook or add more analyses as per your requirements.

