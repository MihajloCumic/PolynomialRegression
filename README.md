# Polynomial Regression

This assignment focuses on polynomial regression and regularization. The dataset `funky.csv` has been provided for this task. There are two main parts: training polynomial regression models of varying degrees and exploring the effects of L2 regularization.

## Dataset
The dataset `funky.csv` is specifically created for the needs of this problem.

## Assignment Breakdown

### a) Polynomial Regression without Regularization

**File:** `polynomial-regression.ipynb`

**Task:**
- Apply polynomial regression to the `funky.csv` dataset with varying degrees of polynomials from 1 to 6.
- The program should output two graphs:
  1. A 2D plot of the dataset along with the regression curves for each of the six polynomial degrees.
  2. A plot showing the dependence of the total cost function (not just at the last training epoch) on the polynomial degree.

### b) Polynomial Regression with L2 Regularization 

**File:** `l2-regularization.ipynb`

**Task:**
- Train a polynomial regression model with a fixed degree of 3, but include L2 regularization (Ridge Regression).
- Test the model with the following values of the regularization parameter `lambda`: {0, 0.001, 0.01, 0.1, 1, 10, 100}.
- The program should generate two graphs:
  1. A 2D plot of the dataset along with 7 regression curves (one for each value of `lambda`).
  2. A plot showing the dependence of the total cost function on the parameter `lambda`.
