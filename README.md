# Statistical Modelling - Final Project

## Authors
- **Arvin Castelo**
- **Semal Shastri**

## Date
December 10, 2024

## Overview
This project explores statistical modeling techniques to determine the key predictors influencing exam scores. We apply multiple linear regression, stepwise model selection (AIC & BIC), Ridge regression, and other statistical methods to analyze the dataset.

## Contents
- **Data Pre-processing**
  - Data Cleaning
  - Data Splitting
- **Summary Statistics and Visualization**
  - Numerical Variables (Scatterplots, Correlations)
  - Categorical Variables (Boxplots, Insights)
- **Multiple Linear Regression**
  - Full Model Analysis
  - Stepwise Selection (AIC & BIC)
  - Ridge Regression
  - Model Comparisons & Diagnostics
- **Inference**
  - Significance Testing
  - Model Assumptions
  - Performance Evaluation

## Methodology
1. **Data Pre-processing**  
   - Removed missing values.
   - Split data into training and test sets.
2. **Feature Selection**  
   - Stepwise selection using AIC and BIC.
   - Ridge regression to address collinearity.
3. **Model Diagnostics**  
   - Residual analysis.
   - Collinearity checks (VIF).
   - Normality and variance testing.

## Key Findings
- **Hours Studied, Attendance, and Previous Scores** are strong predictors of exam performance.
- **Stepwise selection (AIC & BIC) improves model interpretability** by removing insignificant variables.
- **Ridge regression helps with multicollinearity**, but does not drastically improve predictive power.
- **Removal of influential points significantly impacts model fit**, indicating potential outliers in the dataset.
- **Box-Cox transformation did not resolve normality issues**, suggesting an alternative approach might be needed.

## Technologies Used
- **R Programming**
- `tidyverse`, `glmnet`, `car`, `MASS`
- **Statistical Modelling**
- Multiple Linear Regression, Stepwise Selection, Ridge Regression

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   cd your-repo
