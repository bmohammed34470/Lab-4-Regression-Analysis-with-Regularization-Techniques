Project Overview

This lab demonstrates the implementation and comparison of various regression techniques using the Diabetes dataset. The objective is to predict diabetes disease progression based on several health-related attributes and evaluate the effectiveness of different regression models, including regularization methods.

The following regression techniques were implemented:

Simple Linear Regression
Multiple Linear Regression
Polynomial Regression
Ridge Regression
Lasso Regression

Each model was evaluated using standard regression performance metrics and visualization techniques.

Dataset Description

The Diabetes dataset contains 442 patient records with 10 predictor variables and 1 target variable.

Features
AGE – Age of the patient
SEX – Gender
BMI – Body Mass Index
BP – Average Blood Pressure
S1 – Total Serum Cholesterol
S2 – Low-Density Lipoproteins
S3 – High-Density Lipoproteins
S4 – Total Cholesterol / HDL Ratio
S5 – Log of Serum Triglycerides
S6 – Blood Sugar Level
Y – Disease Progression (Target Variable)
Software Requirements
Python 3.x
Google Colab or Jupyter Notebook
Required Libraries
pandas
numpy
matplotlib
scikit-learn

Install packages if necessary:

pip install pandas numpy matplotlib scikit-learn
Project Workflow
Step 1: Data Preparation
Loaded the Diabetes dataset from the uploaded ZIP file.
Explored dataset structure and summary statistics.
Checked for missing values.
Visualized the distribution of the target variable.
Step 2: Simple Linear Regression
Used BMI as the independent variable.
Trained and evaluated the model.
Visualized the regression line.
Step 3: Multiple Linear Regression
Used all predictor variables.
Evaluated model performance.
Compared actual and predicted values.
Step 4: Polynomial Regression
Implemented Polynomial Regression with degree 2 and degree 3.
Compared the results with Simple Linear Regression.
Observed the effect of increasing polynomial complexity.
Step 5: Ridge and Lasso Regression
Implemented Ridge Regression.
Implemented Lasso Regression.
Compared different alpha values.
Evaluated the impact of regularization.
Step 6: Model Comparison

Compared all regression models using:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared (R²)
Results Summary

The experimental results showed that:

Simple Linear Regression produced the lowest prediction accuracy because it relied only on BMI.
Multiple Linear Regression significantly improved prediction accuracy by using all available features.
Polynomial Regression did not improve performance over Simple Linear Regression.
Ridge Regression reduced model complexity while maintaining similar performance.
Lasso Regression achieved the best overall performance with the highest R² value and the lowest prediction error among the evaluated models.
Increasing the regularization parameter (alpha) reduced model complexity but excessive regularization slightly decreased prediction accuracy.
Files Included
Regression_Lab.ipynb      # Jupyter Notebook
diabetes.tab.txt          # Dataset
README.md                 # Project documentation
Conclusion

This lab provided practical experience with several regression algorithms and demonstrated the importance of selecting appropriate predictive features and applying regularization techniques. Multiple Linear Regression, Ridge Regression, and Lasso Regression produced the strongest predictive performance, while Polynomial Regression did not improve accuracy for this dataset. The exercise also illustrated how regularization helps reduce overfitting and improve model stability when working with multiple predictors.
