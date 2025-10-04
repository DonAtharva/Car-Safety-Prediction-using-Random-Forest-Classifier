# Car-Safety-Prediction-using-Random-Forest-Classifier
This project analyzes a car safety dataset to predict whether a car is safe or unsafe using a Random Forest Classifier. The workflow includes exploratory data analysis (EDA), model training, performance evaluation using a confusion matrix, and identification of the most and least important features influencing safety ratings.

# 🚗 Car Safety Prediction using Random Forest Classifier
# 📖 Overview

This project predicts car safety levels based on multiple car attributes using a Random Forest Classifier.
It includes exploratory data analysis (EDA), model training, hyperparameter tuning, confusion matrix evaluation, and feature importance analysis to understand which factors most influence safety ratings.

# ⚙️ Workflow

Data Preprocessing & EDA – Cleaned the dataset, visualized distributions, and handled categorical variables.

Model Training – Trained a Random Forest Classifier for safety prediction.

Hyperparameter Tuning – Tested different parameters to improve model accuracy.

Evaluation – Used a confusion matrix and performance metrics (accuracy, precision, recall, F1-score).

Feature Importance – Identified the most and least important features affecting predictions.

# 📊 Results

The Random Forest Classifier performed better than the baseline model even before hyperparameter tuning, and further improved after optimization.

Key influential features included safety rating and maintenance cost.

Confusion matrix and feature importance plots provided clear interpretability of the model’s performance.

# 🧰 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

# 🚀 Future Improvements

Explore additional algorithms like XGBoost or LightGBM for comparison.

Enhance hyperparameter tuning using GridSearchCV or RandomizedSearchCV.

Deploy the trained model using Streamlit or Flask.
