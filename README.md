# Bank Customer Prediction – Modeling Simulated and Real-world Data

This project was completed as part of my Master's program (MSc in Financial Mathematics, University of Leeds).  
It consists of two parts focused on binary classification:

## 📊 Task 1 – Simulated Classification Task

- Data generated from a nonlinear function using uniform variables
- Visualized checkerboard-like decision boundaries
- Trained and compared three models:
  - CART (Decision Tree)
  - Random Forest
  - XGBoost
- Compared training/testing performance using cross-validation

## 📈 Task 2 – Real Data from Portuguese Bank Marketing Dataset

- Used Kaggle banking dataset to model long-term deposit subscription
- Models:
  - Logistic Regression (GLM)
  - Random Forest
  - Generalized Additive Model (GAM)
- Performed stratified sampling, AUC analysis, variable importance analysis
- Created a simplified model using top 3 most important features

## 📁 Files

- `Data_Learning.Rmd`: Code and results for Tasks
- `Data_Learning.html`: Written reports
- `Portuguese_Bank.csv`: Sample from the original Kaggle dataset

> 📌 Note: All code and analysis are my original work. Data has been partially sampled from the [Kaggle Banking Dataset](https://www.kaggle.com/datasets/rashmiranu/banking-dataset-classification) and used for educational purposes only.
