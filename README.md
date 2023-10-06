Module 12 Report 
Overview of the Analysis
The purpose of this analysis was to determine the loan risk of a client based on other lending activity to determine their creditworthiness. 
The data considered the following features: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt. To begin the data processing the lending dataset was reviewed and split into training and testing data. The logistic regression module was imported from scikit learn and then was applied to the training data, and then predictions were made using the testing data. 
Results
Balanced accuracy scores and the precision and recall scores of all machine learning models.
•	Machine Learning Model 1:
o	The first model had a high precision, recall, and f1 score. It had a recall of 99% of correctly predicted positives, and 100% of actual positives when predicting healthy loans.
•	Machine Learning Model 2:
o	The second model had lower scores when predicting high-risk loans, so out of all the loans classified as being high-risk only 85% were actually risky. The recall was 91% so out of the high-risk loans 91% were correctly classified as high-risk loans. 
Summary
Recommendation based on the results of the machine learning models:
Model 1 has better performance scores than model 2 and is therefore more efficient at predicting healthy loans and actual positives. The biggest problem with trying to choose the correct model is choosing our end goal.
I would not recommend either model because the first one predicts healthy loans, and it would be more beneficial to predict the high-risk loans. When choosing the high-risk loan model 2 is fairly low especially when catching false negatives at 91%. I believe false negatives are more important so if it was a stronger score, I would have suggested model 2.




