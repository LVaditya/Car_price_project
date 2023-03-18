# Car_price_project

#Car Classification Project

The details regarding data set is as follows
1. Dataset file: ‘cars_class.csv’
2. This is a multi-class classification data set.
3. The data set has 719 samples.
4. There are 18 numerical features.
5. The target variable is the class of the car which may be one of: 0 –bus, 1 – Opel Manta, 2 –
Saab, 3 – Van.

The project includes modelling different algorithm to get the best score on test data after training on train data. Different algorithms are tried and after tuning the 
parameteres the one that provides the best score with good values of Mean Squared Error and F1_score is selected.

The algorithms tried are:
-Logistic Regression
-KNN Classifier
-Decision Tree Classifier
-RandomForest Classifier
-Gradient Boosting Classifier

Grid Search CV is used to get good parameters.



#Car Price Regression Project

The details of dataset are
1. Dataset file: ‘cars_price.csv’
2. This is a regression data set.
2. The data set has 206 samples.
3. There are 25 features.
4. The target variable is the price of the car.

This Regression project needs modelling different algorithm to get the best test data score after training on train data. Different algorithms are tried and after tuning 
the parameteres the one that provides the best score with good values of Mean Squared Error and r2_score is selected. Different algorithms were tried and the best one is
determined to be Random Forest.
The algorithms tried are

-Linear Regression
-SGD Regressor
-Ridge Regressor
-Decision Tree Regressor
-RandomForest Regressor
-Gradient Boosting Regressor

In both the projects the concentration is not limited to increasing the score, but to eliminate the condition of overfitting as well as increasing the overall 
performance of the model.
