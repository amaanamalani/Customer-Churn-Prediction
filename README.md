# Customer-Churn-Prediction

Customer Churn Prediction (Telco Dataset)

This project builds a complete machine learning workflow to predict customer churn using the Telco Customer Churn dataset (IBM sample).

The pipeline covers:

Exploratory Data Analysis (EDA): Churn rates across demographics, contract types, tenure, and service usage. Each visualization is paired with a short business takeaway.

Feature Engineering & Preprocessing: Handling missing values, encoding categorical variables, scaling numerics, and creating a stratified train/test split.

Modeling: Logistic Regression, Random Forest, and XGBoost were trained and compared. Metrics used include ROC-AUC, Accuracy, Precision, Recall, and F1-score.

Model Evaluation: Visualizations include ROC curves, confusion matrices, and feature importance rankings, enabling interpretation of how different models perform and what factors matter most.

Key Insights:

Customers on month-to-month contracts and with higher monthly charges show the highest churn likelihood.

Electronic check payments are more strongly associated with churn compared to other methods.

Tenure length is one of the strongest negative predictors of churn (longer tenure = lower churn risk).

Exports for Power BI: Final scored dataset with churn probabilities and aggregated churn statistics is generated for easy integration into a dashboard.

This project is designed as an end-to-end example for data science and analytics portfolios, combining clear analysis, predictive modeling, and export-ready outputs for BI tools.
