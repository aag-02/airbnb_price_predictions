# airbnb_price_predictions

1) Developed predictive models to predict Airbnb prices across 10 European cities using Python. Employed several advanced regression techniques and rigorous data preprocessing steps. 

2) Data Transformation & Outlier Removal: Transformed both target and feature variables to address skewness and the linearity assumption. Identified and removed outliers using IQR method and z-scores.

3) Feature Correlation & Engineering: Underwent detailed correlation analysis to compare effect of transformed and original features against the target variable. Applied one-hot encoding to categorical variables, and transformed non-linear continuous features into binary variables to better capture underlying patterns in the data.

4) Multicollinearity Check & Feature Standardization: Applied VIF to remove severe multicollinear features and standardized features for regression models.

5) Interaction Terms & Feature Selection: Created interaction terms and determined the optimal degree by plotting learning curves. Employed ANOVA and t-tests to check the significance of features and perform feature selection.

6) Regularization Techniques and Model Comparison: Implemented Lasso, Ridge, and Elastic Net regularization. Compared these models with the base linear regression by evaluating train errors, test errors, and R^2 scores. Conducted grid search to find the optimal parameters for regularization techniques. Conducted cross-validation for base Linear Regression model.

7) Remaining Linear Regression Assumptions Testing: Plotted residuals and applied Breusch-Pagan to check for heteroscedasticity. Used the Durbin-Watson test to detect autocorrelation in residuals. Conducted Shapiro-Wilks test and used QQ plots to verify the normality of residuals.
