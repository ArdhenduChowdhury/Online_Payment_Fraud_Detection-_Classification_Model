# Online Payment Fraud Detection

## Introduction
Online payment is the most popular transaction method in the world today. However, with an increase in online payments also comes a rise in payment fraud. The objective of this notebook is **to train machine learning models for identifying fraudulent and non-fraudulent payments**. The dataset is collected from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. 

The dataset consists of 11 variables:
* step: represents a unit of time where 1 step equals 1 hour
* type: type of online transaction
* amount: the amount of the transaction
* nameOrig: customer starting the transaction
* oldbalanceOrg: balance before the transaction
* newbalanceOrig: balance after the transaction
* nameDest: recipient of the transaction
* oldbalanceDest: initial balance of recipient before the transaction
* newbalanceDest: the new balance of recipient after the transaction
* isFraud: fraud transaction
* isflaggedfraud: This column wasnt included in the dataset information that was provided, so we will drop this column as the labeled column is already present.



### Python Libraries
pandas, numpy, seaborn, matplotlib, sklearn

Decision Tree, Logistic Regression and Random Forest were used to identify online payment fraud due to the large dataset.

## Conclusion
The best performing model is **Decision Tree** for identifying fraudulent and non-fraudulent payments.
