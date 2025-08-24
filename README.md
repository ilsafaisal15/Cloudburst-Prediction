**ML Assignment 2 – Cloudburst Prediction**

This repository contains the implementation of ML Assignment 2, focused on analyzing cloudburst events and predicting associated impacts (e.g., deaths) using machine learning techniques.

📌 **Project Overview**

The project involves:

Data Handling – Cleaning, handling missing values, encoding categorical data.

Exploratory Data Analysis (EDA) – Statistical insights, histograms, boxplots, scatterplots, and interactive visualizations.

Feature Engineering – Encoding, normalization, and train-test splitting.

Model Training – K-Nearest Neighbors (KNN), Decision Tree, and Random Forest classifiers.

Feature Importance – Identifying key predictors of fatalities.

Hyperparameter Tuning – Using RandomizedSearchCV to optimize model performance.

Model Evaluation – Accuracy, precision, recall, F1-score, confusion matrix, and ROC curve.

Conclusion – Random Forest achieved the best performance (~70% accuracy), with peak rainfall and duration as the strongest predictors.

🔑 **Key Findings**

Best Model: Random Forest (ensemble learning reduced overfitting).

Top Features: Peak Rainfall (mm/hr), Duration (minutes), and Area (km²).

KNN & Decision Tree: Struggled due to overlapping classes and overfitting.

Hyperparameter Tuning: Boosted accuracy by ~3% across models.

🛠️ **Tech Stack**

Python: Pandas, NumPy, Matplotlib, Seaborn, Plotly

Scikit-learn: Preprocessing, Modeling, Hyperparameter Tuning

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

📊 **Results**

Random Forest outperformed KNN and Decision Tree.

Feature importance highlighted rainfall intensity and duration as critical.

The project demonstrates the full ML pipeline from raw data to evaluation.


