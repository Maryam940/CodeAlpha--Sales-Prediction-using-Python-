📊 Sales Prediction using Machine Learning
🔹 Project Overview

This project predicts future sales based on advertising spend across different channels (TV, Radio, Newspaper, and optionally Target Segment/Platform). The aim is to help businesses make data-driven marketing decisions by analyzing how changes in advertising investments impact sales outcomes.

The project follows a step-by-step workflow:

Data Preparation – Cleaning, transformation, and feature selection.

Exploratory Data Analysis (EDA) – Understanding relationships between ad spend and sales.

Model Training – Regression (Linear Regression, Random Forest) to forecast sales.

Evaluation – Comparing models using RMSE & R² scores.

Insights – Analyzing advertising impact and ROI through feature importance & sensitivity analysis.

Interactive Gradio App – Simple web interface to test different advertising scenarios.

🔹 Features

Predict sales based on TV, Radio, Newspaper spends.

Support for categorical features (Target Segment, Platform) if available.

Compare Linear Regression vs. Random Forest performance.

Visualizations:

Actual vs. Predicted Sales

Residual plots

Feature importance

Sensitivity Analysis – Understand how increasing ad spend affects sales.

Interactive Gradio Interface – User-friendly prediction app.

🔹 Tech Stack

Python (Pandas, NumPy, Matplotlib)

scikit-learn (Regression models, Pipelines, Preprocessing)

Gradio (Interactive Web UI)

Joblib (Model saving/loading)
