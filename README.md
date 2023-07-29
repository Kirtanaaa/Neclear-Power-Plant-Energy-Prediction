# Nuclear-Power-Plant-Energy-Prediction
## Overview

This project aims to predict the energy output of a nuclear power plant using various regression techniques. The dataset contains relevant features, and the goal is to build regression models to accurately predict the energy output based on these features.

## Regression Techniques Used

1. Multiple Linear Regression Model:
   R-squared (R2) Score: 0.932
   Description: Multiple Linear Regression is used to model the relationship between the energy output and multiple independent
   variables. It provides a linear equation that predicts the energy output based on the feature values.

2. Polynomial Regression Model:
   R-squared (R2) Score: 0.945
   Description: Polynomial Regression extends the linear regression model by adding polynomial terms to capture non-linear relationships
   between the features and energy output. It provides a more flexible curve to fit the data.

3. Support Vector Regression (SVR) Model:
   R-squared (R2) Score: 0.941
   Description: SVR is a non-linear regression technique that uses support vectors to approximate the energy output function. It can
   handle non-linear relationships and is effective in capturing complex patterns.
   
4. Decision Tree Model:
   R-squared (R2) Score: 0.921
   Description: Decision Trees create a tree-like structure to make predictions based on the feature values. It is capable of handling
   both numerical and categorical features and provides interpretable results.

5. Random Forest Model:
   R-squared (R2) Score: 0.960
   Description: Random Forest is an ensemble method that combines multiple decision trees to make predictions. It reduces overfitting
   and provides more accurate and robust results.


## Conclusion

The results indicate that the Random Forest model performs the best among all the regression techniques used, achieving a high R-squared score of 0.960. It provides a reliable prediction for the energy output of the nuclear power plant based on the given features. The Polynomial Regression and SVR models also perform well, with R-squared scores of 0.945 and 0.941, respectively. The Decision Tree and Multiple Linear Regression models have slightly lower R-squared scores of 0.921 and 0.932, respectively.

This project demonstrates the importance of exploring multiple regression techniques to select the best model for energy prediction analysis in nuclear power plants. The Random Forest model is recommended for accurate and robust predictions in this context.
