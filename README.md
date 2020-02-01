## Project Specifications

In this Project we will be going over the Lending Club Loan Data where the data is imbalanced, big and has multiple features with different data types. For the purpose of modelling, we will be taking all default loans as the target variable and will  try to predict if a loan will default or not.

## Imbalanced Class problem

Since we are trying to predict if a loan would Default or Not we have to deal with an imbalanced class problem. Class one(minority class) only accounts for 0.07% of the data. We Used SMOTE to generate random samples for our minority class.


## Modeling

After our data is ready for modelling, we used Random Forests Classifier, XG Boost Classifier and LGBM Classifier to make predictions and compared the results to find the best model.
