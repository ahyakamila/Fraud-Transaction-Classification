# Fraud-Transaction-Classification
This Dataset sourced by some unnamed institute. I obtained this data from Kaggle. 
The aim of this project is to classify if the transaction is the fraudlent or not. This dataframe has 8 features including 7 independent & 1 dependent variables.
Feature Explanation:

distancefromhome - the distance from home where the transaction happened.

distancefromlast_transaction - the distance from last transaction happened.

ratiotomedianpurchaseprice - Ratio of purchased price transaction to median purchase price.

repeat_retailer - Is the transaction happened from same retailer.

used_chip - Is the transaction through chip (credit card).

usedpinnumber - Is the transaction happened by using PIN number.

online_order - Is the transaction an online order.

fraud - Is the transaction fraudulent.
The target variable has an imbalanced class. To solve the problem, i proposed an over-sampling technique with the TPOT Classifier with Random Forest.
