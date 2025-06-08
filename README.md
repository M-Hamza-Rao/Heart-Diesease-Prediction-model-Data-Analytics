# 📊 Heart Disease Prediction — UCI Dataset
This repository contains a Python-based machine learning project that predicts the presence of heart disease using the UCI Heart Disease dataset. The project compares multiple classification algorithms and evaluates their performance using various metrics.

📁 Project Structure
Main.ipynb — Jupyter Notebook containing data exploration, preprocessing, model training, evaluation, and improvement attempts.

📦 Dependencies
To run this project, you’ll need:

ucimlrepo

pandas

numpy

matplotlib

seaborn

scikit-learn

Install them via:

bash
Copy
Edit
pip install ucimlrepo pandas numpy matplotlib seaborn scikit-learn
📈 Workflow Overview
Data Fetching

Loads the Heart Disease dataset using ucimlrepo.

Data Exploration

Inspects feature and target datasets for structure and missing values.

Visualizes distributions and correlations.

Preprocessing

Standardizes numerical features using StandardScaler.

Splits data into training and testing sets.

Model Training & Evaluation

Trains multiple models:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Evaluates models using:

Accuracy

Precision

Recall

ROC AUC

Classification Reports

Model Improvement

Experiments with model parameters and approaches for better performance.

📊 Results
Performance metrics for each classifier are displayed in the notebook, along with visualizations and improvement strategies.

📌 Notes
The dataset is sourced directly from the UCI Machine Learning Repository.

Future improvements could include hyperparameter tuning, feature engineering, or trying advanced models like XGBoost.

📑 License
This project is open-source under the MIT License.
