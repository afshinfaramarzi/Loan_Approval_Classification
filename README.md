# Loan_Approval_Imbalanced_Classification


* There are different features (columns) in the datasets. These features include demographic and economic information about a person. Analysis of this data can be done using various machine learning or data analysis techniques.

* For example, classification models can be trained on this data. The data shows whether a loan application has been approved by the people listed in the "approval" column. The data in the columns "age", "job", "marital", "education", "balance", "housing", "duration" and "campaign" describe the characteristics of these people. The effects of these features on loan approval can be explored, and a machine learning model can be trained to predict whether loan applications will be approved.

* Also, relationships between data can be examined. For example, it can be investigated whether there is a correlation between "balance" and "duration". This can help to understand if there is a relationship between a person's bank account balance and loan repayment period.

* As a result, various analyzes can be made on the data we have. Using machine learning techniques, the effect of features in the data on the approval of loan applications can be investigated and prediction models can be built. It can also gain different views on the relationships and features between data, and this information can help develop a loan application evaluation system.

 ## Important explanation about the model and data:

The main purpose of this project is to compare the performance of different ML methods in classification and different techniques in handling imbalanced data.
The data size is small having only <b>4500 samples and 8 features while suffering from skewness. So creating a model with good metrics (e.g. high precision, recall and accuracy) seems not possible for this data set.</b>

## Classification methods used in this project:

* XGboost Classifier
* Neural Networks
* Logisitic Regression
* Random Forest Classifier
* Support Vector Classifier
* Decision Tree Classifier

## Methods for handling skewness used in this project:

* Assigning class weights
* Ensembling Method (BalancedBaggingClassifier)
* Oversampling (SMOTENC)
* Undersampling (NearMiss & Random Undersampling)

## Methods for outlier detection in this project:

* Isolation Forest
* Local Outlier Factor
