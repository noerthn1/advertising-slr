# advertising-slr

## Simple Linear Regression — Advertising vs Sales

## Project Overview

This project demonstrates the implementation and analysis of **Simple Linear Regression** using Python.  
The objective is to model the relationship between TV advertising expenditure and product sales and analyze how a linear model learns patterns from data.

The focus of this project is understanding the **machine learning workflow**, model evaluation, and prediction behavior rather than only generating predictions.

---

## Objectives

- Explore and visualize a real-world dataset
- Build a Simple Linear Regression model
- Understand how linear regression makes predictions
- Evaluate model performance using quantitative metrics
- Analyze prediction errors and model behavior

---

## Dataset

The project uses a public **Advertising dataset**, containing advertising budgets across multiple media channels and corresponding sales performance.

### Features

- `TV` — TV advertising budget (independent variable)
- `Radio` — Radio advertising budget
- `Newspaper` — Newspaper advertising budget
- `Sales` — Product sales (target variable)

This project uses **TV advertising** as the single predictor variable to demonstrate Simple Linear Regression.

The dataset is loaded directly via code to ensure reproducibility.

---

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Project Workflow

1. Data Loading
2. Data Inspection
3. Exploratory Visualization
4. Train/Test Split
5. Model Training
6. Prediction
7. Model Evaluation
8. Error Analysis
9. Model Behavior Visualization
10. Discussion of Limitations

---

## Model Description
Simple Linear Regression models the relationship between variables using a linear equation:
Sales = intercept + slope x TV_Advertising

Simple Linear Regression models the relationship between variables using a linear equation:


The model learns parameters that minimize prediction error between predicted and actual values.

---

## Evaluation Metrics

The model performance is evaluated using:

- **Mean Squared Error (MSE)** — average squared prediction error
- **R² Score** — proportion of variance explained by the model

---

## Key Observations

- TV advertising and sales show a positive linear relationship.
- The regression line captures the overall trend of the data.
- Prediction errors remain due to factors not included in the model.
- Linear regression provides a simple and interpretable baseline model.

---

## Model Behavior Analysis

The project includes:

- Actual vs Predicted comparison
- Residual visualization
- Error magnitude inspection

These steps help evaluate how the model behaves across different input values.

---

## Limitations

- Only one feature is used (Simple Linear Regression).
- Real-world outcomes depend on multiple variables.
- Linear models cannot capture nonlinear relationships.
- Predictions outside observed ranges may be unreliable.

---

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells sequentially.
3. The dataset downloads automatically using code.

---

## Repository Structure
advertising-slr/
│
├── advertising-slr.ipynb
├── README.md
└── requirements.txt


---

## What I Learned

- End-to-end machine learning workflow
- Model evaluation and error analysis
- Understanding prediction behavior
- Practical implementation of regression models

---

## Future Improvements

- Extend to Multiple Linear Regression
- Compare with nonlinear models
- Add feature engineering and model comparison

---

## Author
Nur Sulthan Almuntaha
