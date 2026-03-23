# Interaction Effects in Depression Treatment Outcomes

## Overview
This project investigates whether the relationship between patient age and therapy effectiveness differs across three depression treatments (A, B, and C).

Using linear regression in Python, I compare an additive model with an interaction model, perform model diagnostics, and generate predictions with confidence and prediction intervals.

## Research Question
Does the effect of age on treatment effectiveness depend on the treatment group?

## Dataset
The dataset contains 36 observations with the following variables:

- `age`: age of the patient
- `TRT`: treatment group (A, B, or C)
- `y`: therapy effectiveness score

Source: publicly available teaching dataset used for regression analysis.

## Methods
- Exploratory data analysis
- Additive linear regression model
- Interaction model with age × treatment terms
- Model comparison using R-squared and adjusted R-squared
- Regression diagnostics (residuals, standardized residuals, leverage)
- Prediction with confidence and prediction intervals

## Key Findings
- The interaction model improves the fit substantially compared with the additive model.
- The effect of age differs across treatment groups.
- In particular, treatment C shows a stronger age-related increase in predicted effectiveness than treatment A.
- Diagnostic checks do not indicate major outlier or leverage problems.

## Tools Used
- Python
- pandas
- numpy
- statsmodels
- matplotlib
- seaborn

## Project Structure
- `notebooks/interaction_effects_depression.ipynb`: main analysis notebook
- `requirements.txt`: required Python packages

## How to Run
Open the notebook in Jupyter Notebook, JupyterLab, or VS Code and run the cells in order.