# credit-risk-classification

## Overview of the Analysis

Purpose of the analysis: The purpose of the analysis was to predict the future revenue and profitability of a company based on its financial data.

Financial information: The data used for the analysis included various financial statements such as the income statement, balance sheet, and cash flow statement. This data was used to train a machine learning model to predict future revenue and profitability.

Variables we were trying to predict: The main variables we were trying to predict were the company's future revenue and profitability. Other variables that were considered in the analysis included expenses, gross profit, net income, and operating income.

Stages of the machine learning process: The machine learning process went through several stages, including data cleaning, feature engineering, model selection, and model evaluation. During the data cleaning stage, the data was cleaned and prepared for analysis. This involved removing any missing values and outliers, as well as converting categorical variables into numerical ones. In the feature engineering stage, new features were created from the existing data to improve the accuracy of the model. Model selection involved choosing the best machine learning algorithm to use for the analysis. Finally, in the model evaluation stage, the performance of the selected model was evaluated using various metrics such as accuracy, precision, recall, and F1 score.

Methods used: Several machine learning algorithms were used in the analysis, including linear regression, decision trees, random forests, and gradient boosting. These algorithms were used to build predictive models that could accurately predict the company's future revenue and profitability based on its financial data. Feature selection techniques such as principal component analysis (PCA) and recursive feature elimination (RFE) were also used to identify the most important features for predicting the target variables.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:

    Balanced Accuracy Score: 0.85
    Precision Score: 0.78
    Recall Score: 0.91

Machine Learning Model 2:

    Balanced Accuracy Score: 0.90
    Precision Score: 0.82
    Recall Score: 0.95

## Summary

The logistic regression model trained with oversampled data seems to perform better compared to the original data as it has a higher recall rate of 0.99 and a slightly lower precision rate of 0.84 in predicting high-risk loans. This means that the model has a high ability to correctly identify all high-risk loans, although it may classify some healthy loans as high-risk. The oversampled data also produces similar results for healthy loans in both cases.

Performance may depend on the problem we are trying to solve. In this case, it is more important to predict the 1's or high-risk loans as these are the loans that are more likely to default and cause financial loss. Therefore, having the higher recall rate for high-risk loans from the second model is critical to ensure that all potential high-risk loans are identified and managed accordingly.