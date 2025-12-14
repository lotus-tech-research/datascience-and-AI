# datascience-and-AI
Machine Learning: Classification & Regression
Decision Tree, KNN, Random Forest — Full Comparison
Part of the datascience-and-AI repository

🚀 Overview
This project demonstrates two core machine learning workflows:

✅ 1. Classification — Heart Disease Prediction
Models used:

Decision Tree Classifier

KNN Classifier

Random Forest Classifier

Goal: Predict whether a patient will develop heart disease within 10 years.

✅ 2. Regression — House Price Prediction
Models used:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Goal: Predict house prices based on features such as bedrooms, bathrooms, square footage, etc.

▶️ Run the Notebook in Google Colab
Paste your notebook link here:

markdown
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](PASTE_NOTEBOOK_LINK_HERE)
📂 Project Structure
Code
datascience-and-AI/
│
├── classification_regression_comparison.ipynb   # Your full notebook
├── heartdisease.csv                             # (optional) dataset
├── House Price Prediction.xlsx                  # (optional) dataset
└── README.md
🧠 Section 1 — Classification (Heart Disease)
✅ Steps performed:
Load and clean dataset

Handle missing values

Explore class imbalance

Split into train/test

Train 3 models

Evaluate using:

Accuracy

Precision

Recall

F1 Score

Compare all models in a summary table

✅ Example Comparison Table
Model	Accuracy	Precision	Recall	F1 Score
Random Forest	0.78	0.74	0.72	0.73
Decision Tree	0.72	0.51	0.51	0.51
KNN	0.69	0.48	0.47	0.47
(Values will depend on your dataset.)

🏠 Section 2 — Regression (House Prices)
✅ Steps performed:
Load dataset

Remove non‑useful columns

Scale features and target

Train-test split

Train 3 regression models

Evaluate using:

MAE

RMSE

MAPE

Compare all models in a summary table

✅ Example Comparison Table
Model	MAE	RMSE	MAPE
Random Forest	0.021	0.041	0.018
Decision Tree	0.034	0.059	0.031
Linear Regression	0.067	0.089	0.062
(Values depend on scaling and dataset.)

📊 Visualizations Included
Target distribution bar chart

Model performance bar charts

Regression error comparison

✅ How to Use This Notebook
Open the notebook in Colab

Upload the datasets (if needed)

Run all cells

Review model comparisons

Modify parameters to experiment

🔮 Future Improvements
Add hyperparameter tuning (GridSearchCV / RandomizedSearchCV)

Add cross‑validation

Add feature importance visualizations

Add more models (XGBoost, LightGBM, SVM)

Add interactive dashboards (Plotly / Streamlit)

👤 Author
This project is part of the datascience-and-AI repository created by Lotus.
