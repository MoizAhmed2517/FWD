# Fraudulent Wine Detection Algorithm

IF we use the values of GridsearchCV our model in case of fraudulent wine detection its fails. The reason behind the failure in unbalance classes hence we need to introduce the class_weight concept Initially, assuming class_weight to be balanced once deep dive into hyperparameter tuning will improve the overall model working.

### Next steps are as follows:

1. Hyperparameter tuning of SVC
2. Change of algorithm
3. Move back to EDA and do feature engineering in more detail
4. Repeat step#1 after selecting best model

## Final SVM Results

Parameters: C = 0.8 and Kernel = rbf   --> f1-score = 0.26, accuracy = 0.84, Fraud: (Precision: 0.16 , Recall: 0.67)
Parameters: C = 0.115 and Kernel = poly(3)   --> f1-score = 0.31, accuracy = 0.9, Fraud: (Precision: 0.21 , Recall: 0.56)
