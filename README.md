# ❤️ Heart Disease Prediction using Machine Learning
This project aims to predict whether a person is likely to have heart disease based on clinical and demographic data such as age, blood pressure, cholesterol levels, chest pain type, etc. The objective was to apply classification algorithms to a healthcare dataset and understand how ML can assist in early diagnosis.

# Project Workflow
1. Data Understanding & Exploration
Dataset included 13+ features like age, sex, cp (chest pain type), thalach (max heart rate), etc.

Conducted Exploratory Data Analysis (EDA) to check for class imbalance, missing values, correlations, and outliers.

2. Data Preprocessing
Imputation: Handled missing or zero values where appropriate.

Encoding: Used pd.get_dummies for nominal categorical features like chest pain and slope.

Scaling: Applied StandardScaler to numerical features to normalize ranges (important for distance-based models).

Train-test split: 80/20 or 70/30 split to assess generalization.

# ✅ Why Random Forest?
Random Forest was chosen because:

It performs well on tabular data and handles both categorical and numerical features.

It is less prone to overfitting compared to single decision trees.

It provides feature importance, helping identify key predictors like chest pain type, thalach, and exang (exercise-induced angina).

# Key Learnings
Learned to preprocess medical data, which can have noisy, missing, or skewed distributions.

Understood how to select and evaluate classification models under real-world constraints.

Gained intuition around model interpretability using feature importance.

Applied evaluation metrics relevant to healthcare where stakes are high.

# Next Steps
Test with models like Logistic Regression, XGBoost, or SVM for comparison.

Perform hyperparameter tuning using GridSearchCV.

Consider building a Streamlit app to allow users to input values and get predictions.
