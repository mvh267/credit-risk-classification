# Credit Risk Analysis Project #
## Overview ##
This project focuses on developing a machine learning model to assess credit risk. The primary objective is to predict the likelihood of a loan being at high risk of defaulting, using logistic regression. The analysis aims to assist in making informed decisions in the lending process.

## Repository Structure ##
credit_risk_classification.ipynb: Jupyter notebook containing the analysis and modeling process.
lending_data.csv: Dataset used for the analysis.
README.md: This file, providing an overview and results of the project.
## Analysis and Results ##
Data Preparation:
-The data was loaded from lending_data.csv into a Pandas DataFrame.
-Labels (y) were created from the loan_status column, and features (X) were derived from the remaining columns.
-The dataset was split into training and testing sets using train_test_split.
Logistic Regression Model:
-A logistic regression model was fitted using the training data.
-Predictions were made on the testing data, and the model's performance was evaluated.
## Model Evaluation ##
Confusion Matrix: Provided detailed insights into the model's prediction accuracy for both classes.
Classification Report:
-Precision for healthy loans (0): 100%
-Precision for high-risk loans (1): 87%
-Overall balanced accuracy: 94%
## Conclusion and Recommendations ##
The logistic regression model demonstrated high effectiveness in predicting healthy loans with perfect precision and was also fairly accurate in predicting high-risk loans. The balanced accuracy of 94% indicates a strong overall performance. This model is recommended for use in credit risk assessment, with the understanding that while its precision for high-risk loans is lower, it still provides valuable insights.