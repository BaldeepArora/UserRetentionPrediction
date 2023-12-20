# UserRetentionPrediction

### Problem Statement
The dataset used in this analysis is for a specific telecommunication company with customer attributed. There are features such as customer location, voice calls, voice messaging, conversational activity and grievance reports. The target feature is whether the customer will close the account or not. 
Based on the behaviour of a customer during their tenure with this telecommunication company, it is possible to predict whether the account will be closed or not.

### Contents Covered:

1. Importing Libraries

2. Data Cleaning
   <br> - Duplication
   <br> - Missing values
   <br> - Outliers

3. Exploratory Data Analysis

4. Feature Engineering
   <br> - Correlation
   <br> - Encoding
   <br> - Scaling
   <br> - Train test split

6. Model Building
  <br> - Base Model Creation
  <br> - Class Imbalance Handling
  <br> - Regularization (Ridge & Lasso)
  <br> - Grid Search Cross Validation
  <br> - 10 Fold Cross Validation

7. Conclusion

### Conclusion
This analysis was done to obtain the best fit model on this dataset. The grid search selected the optimal hyperparamters for the penalty, solver and c value from the provided values. On using these parameters we observed the model has improved. To build confidence in the result of ths model, a 10 fold was done that gave us an average accuracy of 85%. 


This model predicts whether an account of a current customer will continue for the next billing cycle. It uses features like the location of the customer, relationship of the customer with the company, communication activity of the customer on their current plan as well as any complaints they might have submitted. 85% of the time the model is accurate in predicting whether a certain customer with the above traits would close their account or not.
