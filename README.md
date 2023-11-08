## Credit Card Approval Predictor
### Overview
Building automatic credit card approval predictor using machine learning techniques: Logisitc regression model and Xgboost classification.

Dataset: https://archive.ics.uci.edu/dataset/27/credit+approval

Commercial banks often receive numerous credit card applications, and many are rejected for various reasons, such as high loan balances, low income levels, or excessive inquiries on a credit report. Manual application analysis can be time-consuming, error-prone, and inefficient, making it a prime candidate for automation using machine learning.

### Process
The project utilizes the Credit Card Approval dataset from the UCI Machine Learning Repository. The primary objectives include:

1. Data Loading and Exploration: The dataset is loaded and inspected to understand its structure, data types, and missing values.
2. Data Preprocessing: Missing values are handled through imputation, transforming non-numeric features into numeric, and scaling the feature values.
3. Model Building: A logistic regression model is trained on the preprocessed data to predict credit card approvals.
4. Model Evaluation: The model's performance is assessed, and its accuracy is calculated. In this case, it achieved an accuracy score of 86.12% accuracy with logistic regression and improved to 87.23% with XGBoost algorithm.
5. Hyperparameter Tuning: Grid search is performed to optimize the model's hyperparameters, further improving its predictive capability.
6. Best Model Selection: The best-performing model with the optimal hyperparameters is identified.

The project is a practical demonstration of data preprocessing, model building, and hyperparameter tuning for credit card approval prediction. The achieved accuracy highlights the potential for using machine learning to automate and enhance the credit approval process in the financial industry.
