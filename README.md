# Loan-Status-Prediction

# Overview
This repository contains code for predicting loan status based on a dataset. The code includes data preprocessing, exploratory data analysis (EDA), and the implementation of various machine learning models for prediction.

# Getting Started
- Clone the repository:
``
git clone https://github.com/your-username/loan-status-prediction.git
cd loan-status-prediction
``
- Install the required libraries:
```
pip install -r requirements.txt
```
# Dataset
The dataset used for this project is named "Loan Status Prediction.csv" and contains information about loan applicants. It includes attributes such as Gender, Marital Status, Education, Applicant Income, Coapplicant Income, Loan Amount, and more.

# Exploratory Data Analysis
- The dataset has 614 entries and 13 columns.
- Descriptive statistics and data types of columns are provided.
- Missing values are handled using appropriate strategies.
- Data visualizations include count plots, histograms, and box plots to - - - understand the distribution of variables.
# Data Preprocessing
- Replaced "3+" in the Dependents column with "4".
- Dropped the Loan_ID column.
- Handled missing values using mode and mean imputation.
- Applied square root transformation to skewed numerical variables.
# Data Visualisation
- Visualized data using count plots for categorical variables.
- Explored relationships between Education, Gender, Marital Status, and Loan Status.
# Model Building
Implemented the following machine learning models:

- Logistic Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- K-Nearest Neighbour (KNN)
- Categorical Naïve Bayes
# Model Comparison
- Compared model performance based on accuracy scores.
- The Logistic Regression model achieved the highest accuracy.
# Usage
You can use the provided Jupyter notebook or script to run the code. Adjustments and improvements can be made based on your specific requirements.

# License
This project is licensed under the [License Name] - see the LICENSE.md file for details.

# Acknowledgments
Special thanks to [anyone who contributed or inspired the project].
