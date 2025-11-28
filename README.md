📊 Portuguese Bank Marketing Prediction Project

This project predicts whether a customer will subscribe to a term deposit based on the Portuguese Bank telemarketing dataset.
It includes data analysis, preprocessing, model building, evaluation, and insights useful for marketing strategy.

📌 Project Overview

The Portuguese Bank conducted telemarketing campaigns to promote term deposits.
Using this dataset, the project aims to:

Understand customer behavior

Identify key factors influencing subscription

Build ML models for prediction

Compare model performance

Provide data-driven insights for marketing improvement

📁 Repository Structure

├── data/
│   └── bank-additional-full.csv   # Dataset (optional to upload)
├── notebooks/
│   └── Portuguese Bank Marketing Code.ipynb
└── README.md

📦 Dataset

The dataset used is from the UCI Machine Learning Repository:
https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

🔍 Exploratory Data Analysis (EDA)

The notebook performs:

Distribution analysis of features

Customer job, marital status, education patterns

Campaign and call duration analysis

Correlation heatmaps

Subscription ratio analysis (imbalanced target)

🛠️ Machine Learning Workflow
1. Preprocessing

Handling missing values

One-Hot Encoding for categorical features

Splitting into train/test sets

Balancing techniques (if required)

2. Models Trained

Logistic Regression

Random Forest

Gradient Boosting / XGBoost

Additional baseline classifiers

3. Evaluation Metrics

Accuracy

F1-Score

Confusion Matrix

Feature Importance

📈 Results & Insights

Tree-based models generally perform best

Features like duration, poutcome, age, month, and contact type influence results

Dataset imbalance plays a major role, so handling it improves predictions

Insights help improve customer targeting and marketing efficiency


