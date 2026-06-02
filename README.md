# spotify-popularity-analysis
# Statistical Modeling & Econometrics in R

This repository contains a collection of advanced statistical modeling and data analysis scripts developed in R. The projects demonstrate proficiency in hypothesis testing, regression analysis, econometric diagnostics, and simulation methods.

## 📂 Projects Overview

### 1. Monte Carlo Simulation & Likelihood Ratio Test
* **Description:** Developed an asymptotic Likelihood Ratio test to distinguish between two Beta distributions. Analytically derived the Fisher Information and calculated the minimax sample size.
* **Key Techniques:** Monte Carlo simulations (10,000 iterations) to refine the asymptotic decision thresholds and calculate empirical statistical power.[cite: 9]
* **File:** `monte_carlo_hypothesis_testing.R`

### 2. Feature Engineering & Multicollinearity Resolution
* **Description:** Diagnosed a failed multiple regression model that suffered from severe multicollinearity between predictors (study hours and pages read).[cite: 7]
* **Key Techniques:** Scatterplot matrix diagnostics, Feature Engineering (created a `ReadingSpeed` metric), and robust model fitting. The engineered feature successfully transformed a statistically insignificant model into a highly predictive one.[cite: 7]
* **File:** `regression_multicollinearity_fix.R`

### 3. Non-linear Regression & Structural Break Testing (Chow Test)
* **Description:** Addressed severe heteroscedasticity and right-skewness in real household survey data by transitioning to log-log econometric models.[cite: 5]
* **Key Techniques:** Logarithmic transformations, residual diagnostics (Q-Q plots, histograms), and Chow Test application to detect structural breaks across demographic groups.[cite: 5, 6]
* **File:** `log_log_regression_chow_test.R`

## 🛠️ Technologies & Libraries
* **Language:** `R`
* **Libraries:** `car`, `stats`, base R graphics.
