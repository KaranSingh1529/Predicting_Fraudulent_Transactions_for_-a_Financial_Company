# Predicting_Fraudulent_Transactions_for_-a_Financial_Company

Analysis
I have used different Machine Learning Models to detect the fruad transaction that are taking place.

To choose which variable is best for model feature selection was used. Top variable comes out are - oldbalanceOrg, newbalanceOrg, type_PAYMENT, type_TRANSFER

The Model Built are Logistic Regression Model, Decision tree and Random Forest. Random forest and Decision Tree modelperform best on train as well as on test data.

The performance of the model is checked by ROC AUC score, Accuracy, F1 Score, Precision and recall.

The key factor that are used to detect fraud transcation are type_PAYMENT, type_Transfer it can be detected that fraudster are using are common type of payment and transfer menthod to do the fraud.

The prevention can be using 2 step of verification having a more watch on payment and transfer menthod. Having a eye on how a normal person do a transaction by keeping a watch on there oldbalanceOrg and newbalanceOrg. If there is something unusual detected use 2 step verification for that process.

When these things are implemented the data shoulded be collected again and should be perform again on the model. It will attain the better accuracy,precision and recall value from the past it scored.

FLOW OF ANALYSIS

Data cleaning and data manipulation.
Check and handle duplicate data.
Check and handle NA values and missing values.
Drop columns. If it contains large amount of missing values and not used for analysis.
Imputation of the values.
EDA
Univariate data analysis,values_count,distribution of variable.
Bivariate data analysis,correlation coefficients and pattern between the variable.
Feature Scaling and Creating Dummy Variable.
Performed Oversampling.
Building Model: Logistic regression, Decision Tree, Random forest Model used for the model making and prediction.
Validation of the model.
