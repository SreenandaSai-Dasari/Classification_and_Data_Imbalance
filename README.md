# Classification_and_Data_Imbalance:

This project uses a real time Housing project data consisting of 80 Independent variables and 1 target variable (house_price). The main aim of this project is to prepare a roadmap for end-to-end ***Linear Regression*** model that includes steps such as ***Data Cleaning***, ***Exploratory Data Analysis***, ***Data Modeling***, ***Linear Regression Assumptions***, ***Building a Linear Regression model*** and ***Hyperparameter Tuning***, ***Model Evaluation***

This project also covers the regularization methods such as ***Ridge and Lasso Regression***. I will check how these regularization functions impact a normal Linear Regression Model by comparing the ***r2-score***, ***adjusted r2-score*** and ***coefficients*** of all three models.

## Further, I am listing down steps in each phase here:

* **Data Cleaning:**               Handling Null values, Removing Duplicates, Checking for Data Imbalance, Performing Sanity Checks, Feature Selection & Feature Engineering.

*  **Exploratory Data Analysis:**  Consists of Univariate, Bivariate and Multivariate Analysis. I have used line, bar, pair, histogram plots and heat map in this step.

*   **Data Modeling:**             In this step, I have performed operations such as creating Dummy variables, Scaling and train - test split to get the modeling stack ready.

After performing all the above steps, the final modeling stack has 145 columns, so I have done quick correlation check against target variable and reduced the stack to 75 variables. Then, I have created a simple linear regression model with out any tuning.


*  **Linear Regression Assumptions:**   In this step, I did few checks such as VIF, checking for independece of target variable values, Homoscedasticity and the Distribution of error terms

*  **Hyperparameter Tuning:**           I have used Recursive Feature Elimination method along with Grid Search technique to determine the optimal number of features to be used in the model.

Then, I have created a Ridge and Lasso regression models using the same number of variables determined by RFE method and tuned the hyperparameters for them.

* **Model Evaluation:** I have used metrics such as r2 score, adjusted r2 score, MAPE and coefficents to compare the performance of the above three models.

# Conclusion:

Lasso and Ridge regression are regularization techniques whose primary aim is to reduce the complexity and increase the effectiveness of the model. So, we may not see much difference in metrics such as MAPE, r2 score but these functions try to increase efficiency of the model by punishing the insignificant variables. Ridge regression does this by reducing the coefficients of the insignificant variables where as lasso can zero out the coefficients of insignificant variables which makes it a good tool for feature selection.

  
