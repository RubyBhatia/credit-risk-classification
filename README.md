# credit-risk-classification
**Challenge-20
Overview of the Analysis**
In this Challenge, I have used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

This Challenge is divided into the following subsections:

1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
3. Write a Credit Risk Analysis Report

1. Split the Data into Training and Testing Sets
- Open the starter code notebook and use it to complete the following steps:
- Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining 
   columns.
- Split the data into training and testing datasets by using train_test_split.

2. Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
- Fit a logistic regression model by using the training data (X_train and y_train).
- Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
- Evaluate the model’s performance by doing the following:
- Generate a confusion matrix.
- Print the classification report.
- Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high- 
   risk loan) labels?

**Result and Summary**

The evaluation of the ‘logistic regression model’ for credit risk grouping uncovered that its implements outstandingly good in classifying “Beneficial” loans, completing 100% accuracy, evoke and precision for this grouping. Still, the model is inadequate at expecting in loans which are on very high risk, with a precision of 87% and an overall f1-score of 91%. The main weakness remains in its false positive-86 occurrences where it inadequately considered as a beneficial loan due to high-risk. This has a major impact on its efficiency to steadily distinguish between high-risk, healthy loans, specifically in high-risk projections. 







  
