📊 RIDGE,LASSO & POLYNOMIAL ANALYSIS:

📝OVERVIEW:

This project applies Ridge, Lasso, and Polynomial Regression on various datasets to handle multicollinearity, perform feature selection, and model non-linear relationships. Models are evaluated using R² and RMSE.

✨ KEY FEATURES:

🟦 Ridge Regression: Handles correlated features, finds optimal alpha via cross-validation.

🟪 Lasso Regression: Performs feature selection by shrinking irrelevant coefficients to zero.

🟩 Polynomial Regression: Models non-linear relationships and compares with linear fit.

📏 Evaluation: Coefficients, intercept, R², and RMSE reported for all models.




⚙️ REQUIREMENTS:

Python >= 3.8

Libraries: numpy, pandas, matplotlib, scikit-learn, jupyter

Install via:

pip install numpy pandas matplotlib scikit-learn jupyter





✨ SCRIPTS & FEATURES

TASK 1:🟦 Ridge Regression (2 correlated features)

Dataset: ridge_correlated_150.csv

Finds best alpha via cross-validation.

Outputs coefficients, intercept, R², and RMSE.



TASK 2:🟦 Ridge Regression (10 features)

Dataset: ridge_10feat_150.csv

Handles multiple features, finds best alpha.

Evaluates model performance with R² and RMSE.



TASK 3:🟪 Lasso Regression (sparse features)

Dataset: lasso_sparse_150.csv

Performs automatic feature selection.

Reports selected features, R², and RMSE.



TASK 4:🟪 Lasso Regression (grouped features)

Dataset: lasso_groups_150.csv

Standardizes features before Lasso.

Reports coefficients on original scale, intercept, R², and RMSE.




TASK 5:🟩 Polynomial Regression (quadratic)

Dataset: poly_quadratic_150.csv

Compares linear vs. quadratic fit.

Reports coefficients, intercept, R², RMSE, and predicts new values.


✏️AUTHOR

SRI VARSHA P
