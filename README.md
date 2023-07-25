# Mercedes_benz

### Title: Mercedes-Benz XGBoost Model with GridSearchCV

Introduction:

In this project, we will be building an XGBoost model to predict the time taken for a car's test. We 
will use the Mercedes-Benz Greener Manufacturing dataset which contains various features of the 
car and the test, such as the ID, car model, test time, etc
We are going predict to the time it takes for a car's testing phase in the production line, which will 
help Mercedes-Benz to optimize their manufacturing process and reduce the time-to-market for 
their cars.
The dataset provided for this project has over 4209 observations and 378 features, making it a 
challenging task to find the most relevant features to use in the model.

Steps:

1. Import the necessary libraries such as pandas, numpy, xgboost, etc. 
2. Download the Mercedes-Benz Greener Manufacturing dataset and import it.
3. Preprocess the data by encoding categorical variables, dropping low variance values.
4. In general, multicollinearity (high correlation among IVs) can cause issues in regression 
analysis, including unstable parameter estimates, decreased model interpretability, and 
reduced predictive power.
5. If two independent variables have a correlation coefficient of more than 0.9, this indicates 
that they are very strongly related to each other. In such cases, it may be appropriate to 
consider removing one of the variables to address the issue of multicollinearity.
6. Checked unique and null value in datasets.
7. Split the data into training and testing sets using the train_test_split() function from the 
scikit-learn library.
8. Build an XGBoost model with hyperparameters using GridSearchCV to find the optimal 
hyperparameters for the model.
9. Evaluate the performance of the XGBoost model using various metrics such as RMSE, R2 
score, etc.

Conclusion:

In this project, we built an XGBoost model with hyperparameters using GridSearchCV to predict the 
time taken for a car's test. We evaluated the performance of the model using various metrics and 
achieved good results (58%). This model can be used to make predictions on new data and improve 
the efficiency of the testing process.
