# Module 12 Report Template

## Overview of the Analysis
The purpose of this analysis was to build a machine learning model to analyze the risk of loans and predict whether or not a loan is high risk, which is 1 in the data, or healthy, which is 0 in the data. The csv included columns such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. These columns provided financial data that helped to classify loans into either high-risk or healthy categories. The different stages of the machine learning process I went through included creating the labels set, y, and the features, x. Next, spliting the dat into training and testing datasets. Lastly, I created a logistic regression model with the original data and evaluated the model's performance.
## Results

* Machine Learning Model (Logistic Regression Model):
    * Description of Model 1 Accuracy, Precision, and Recall scores. 
    * Accuracy: 99%
    * Precision: 0: 100%, 1: 86%
    * Recall: 0: 99%, 1: 94%
    Since the precision & recall are high for both 0 (healthy) and 1 (high-risk loans), the model performs very well as we can see by the accuracy percentage.




## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

* The results of the logistic regression model are promising because it has a 99% accuracy rate. Performance does depend on the problem we are trying to solve. For example, if determining which are high-risk loans are more important, a model with high recall for the value 1 is best.
However, if avoiding misclassification of healthy loans is more important, a model with high precision for the value 0 is preferred.


