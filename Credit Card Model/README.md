# Credit Card Approval Prediction: Project Overview
![Credit Card Approval](Image/creditcard.jpg "Credit Card Approval")
* The project aims to predict how likely a credit card request will get approved based on age, gender, credit score, income, debt, etc.
* Explored the data to understand the relationship of various features with the target (Approval Status)
* Imputed the missing values with mean imputation for the numeric features and  mode imputation to categorical features
* Implemented MinMax Scaling to the features.
* Optimized Logistic Regression using GridsearchCV to obtain the best model.

## DataSet Source:
The dataset is <a href="http://archive.ics.uci.edu/ml/datasets/credit+approval" target="_blank">Credit Card Approval dataset</a> from the UCI Machine Learning Repository. The data consists of 16 columns and 160 records.

## Resources Used
**Python Version:** 3.7 </br>
**Packages Used:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Model Building
Built a dataframe for our model with relevant columns.

Transformed the categorical variables into dummy variables. In addition, the data was split into train and test set.

Performed classification analysis using Logistic Regression and used GridSearchCV to increase accuracy.

## Model Performance
  * Logistic Regression: Accuracy = 85.99%
  * Using GridSearchCV : Accuracy = 85.99%
  
## Conclusion
On applying the logistic model, we have achieved the accuracy of 86% which is significantly high for predicting how likely a credit card request will get approved.
