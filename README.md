# -BPM-Prediction-Mastery-Data-Harmonization-Advanced-Ensemble-Techniques
BPM Maestro is a comprehensive machine learning solution for predicting song tempo (Beats Per Minute) from audio features. This project demonstrates advanced techniques in feature engineering, model ensembling, and prediction optimization that achieved top-tier performance in the Kaggle Playground Series S5E9 competition.



📘 Overview

This project was developed as part of the Kaggle competition “Problematic Internet Use” hosted by the Child Mind Institute.
The goal is to predict problematic internet usage among adolescents based on a variety of psychological, behavioral, and demographic features.

The notebook focuses on data harmonization, exploratory data analysis (EDA), feature engineering, and the construction of an ensemble model to improve predictive performance through blending.

⚙️ Project Workflow
1️⃣ Data Harmonization

Combined multiple datasets with different structures.

Standardized column names and formats.

Handled missing values and corrected inconsistencies in the data.

2️⃣ Exploratory Data Analysis (EDA)

Visualized the distribution of main variables.

Studied correlations between demographic and behavioral features.

Identified potential patterns linked to problematic internet use.

3️⃣ Feature Engineering

Created new meaningful features to enhance the model’s learning capacity.

Encoded categorical variables and normalized numerical features.

Removed irrelevant or redundant variables.

4️⃣ Model Building & Ensemble Learning

Trained multiple base models including LightGBM, XGBoost, and CatBoost.

Applied blending/stacking techniques to combine model predictions.

Evaluated models using cross-validation and competition metrics.

🧩 Tools & Libraries

Python

Pandas, NumPy, Matplotlib, Seaborn – data processing & visualization

Scikit-learn – model training and evaluation

LightGBM, XGBoost, CatBoost – machine learning algorithms

Joblib, Optuna – model saving & hyperparameter tuning

📊 Results

Achieved a strong predictive performance through ensemble blending.

Improved robustness and generalization compared to individual base models.

Highlighted the most influential features related to internet usage patterns.

🧠 Key Insights

Feature harmonization significantly improves model stability.

Combining multiple algorithms through blending yields better performance.

Certain psychological indicators show strong correlations with problematic use.
