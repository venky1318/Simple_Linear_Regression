# Task 33 — Salary Prediction Using Simple Linear Regression

## Project Overview

This project demonstrates Simple Linear Regression using Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

A Salary vs Experience Dataset is used to build a supervised machine-learning regression model that predicts an employee's annual salary based on years of work experience.

The project covers dataset preparation, training and testing data separation, model training, salary prediction, model evaluation, and regression visualization.

## Objectives

- Understand Simple Linear Regression.
- Prepare a numerical dataset.
- Select one input feature and one numerical target.
- Split the dataset into training and testing sets.
- Train a Linear Regression model.
- Predict salaries using test data.
- Evaluate model performance.
- Visualize the regression line.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Dataset Description

The project uses a manually created dataset containing 20 fictional employee records.

| Column | Description |
|---|---|
| years_experience | Total years of work experience |
| annual_salary_inr | Annual salary in Indian Rupees |

## Feature and Target Selection

**Input Feature (X):** `years_experience`

**Target Variable (y):** `annual_salary_inr`

Years of experience is used as the input because it provides information about an employee's professional experience.

Annual salary is selected as the target because it is the numerical value the model attempts to predict.

## Model Used

The project uses Simple Linear Regression from:

`sklearn.linear_model.LinearRegression`

The model learns a linear relationship between experience and salary.

The regression equation is:

**Y = mX + C**

Where:

- Y represents predicted salary.
- X represents years of experience.
- m represents the regression coefficient or slope.
- C represents the intercept.

## Model Training

The dataset is divided into:

- 80% training data — 16 records.
- 20% testing data — 4 records.

The model is trained using `fit()` and predictions are generated using `predict()`.

## Model Evaluation

| Metric | Result |
|---|---:|
| MAE | ₹5,561.38 |
| MSE | 31,029,545.81 |
| RMSE | ₹5,570.42 |
| R² | 0.9997 |

The metrics are obtained using the specified sample dataset and training/testing split.

## Regression Model Parameters

| Parameter | Value |
|---|---:|
| Slope | 40,040.72 |
| Intercept | 2,65,184.74 |

## Prediction Example

For an employee with 12 years of experience, the model predicts an annual salary of approximately ₹7,45,673.35.

## Project Files

- `Task_33_Simple_Linear_Regression.ipynb` — Complete Google Colab notebook.
- `salary_experience_dataset.csv` — Original employee dataset.
- `regression_predictions.csv` — Actual and predicted salary results.
- `model_summary.csv` — Model parameters and evaluation metrics.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.
- `project_report.pdf` — Formal project report.
- `charts/salary_regression_line.png` — Regression line visualization.
- `screenshots/` — Actual execution evidence.

## Conclusion

This project demonstrates how Simple Linear Regression can be used to predict a numerical target using one numerical input feature.

A regression model is trained to estimate annual salary from years of experience.

The project provides practical experience in supervised machine learning, model training, prediction, evaluation, and visualization.

**Note:** The dataset is synthetic and designed to demonstrate a near-linear relationship. Real-world model performance may differ.
