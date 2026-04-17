# crop-yield-prediction-ml

🚀 Overview

This project develops a machine learning pipeline to predict crop yield (hg/ha) using multi-year agricultural data across multiple countries.

It leverages environmental, chemical, and categorical features to model complex relationships affecting crop production.

🛠 Tech Stack


Language: Python

Libraries:pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost

📂 Dataset

Multi-country agricultural dataset (1990–2013)

~26,000+ samples


⚙️ Methodology

🔹 Data Preprocessing

Removed irrelevant columns

Handled skewed distributions

Label encoding for categorical variables

Filtering low-frequency countries

🔹 Feature Engineering

Climate features (rainfall, temperature)

Chemical inputs (pesticides)

Temporal trends (year-wise data)

🔹 Models Used

📌 Baseline Models

Linear Regression

KNN

📌 Tree-Based Models

Decision Tree

🚀 Ensemble Models

Random Forest

Gradient Boosting

XGBoost

Bagging Regressor
