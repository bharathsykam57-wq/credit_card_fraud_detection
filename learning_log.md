## Day 1 – Project Setup & Understanding Data
- Created the repository structure and added an initial notebook/script for experimentation.
- Reviewed the credit card fraud detection problem: highly imbalanced binary classification where fraud cases are rare compared to normal transactions.
​- Noted key goals: handling class imbalance properly, build baseline models, and focus on precision/recall and AUC instead of accuracy.
## Day 2 – EDA & Data Preprocessing
Loaded the dataset and performed initial exploratory data analysis to understand feature distributions, correlations, and class imbalance.

Checked for missing values, inspected outliers, and reviewed anonymized features (V1–V28), transaction amount, and time to guide preprocessing decisions.

Created baseline visualizations (class count plots, amount distributions) and decided on a strategy for train–test split that preserves the minority fraud class.
## Day 3  
Implemented a baseline fraud detection model (e.g., Logistic Regression/Random Forest) with class weighting, evaluated using precision, recall, F1-score, ROC-AUC, and confusion matrix with focus on fraud-class recall.
​
Explored decision threshold tuning and precision–recall trade-offs, and noted next steps like trying resampling methods (SMOTE/undersampling) and more advanced models (e.g., XGBoost) with cross-validation.
​
