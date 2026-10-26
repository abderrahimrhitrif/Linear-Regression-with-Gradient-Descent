# Linear Regression with Gradient Descent

## Overview
This project demonstrates a foundational implementation of univariate and multivariate linear regression optimized via gradient descent in Python and Jupyter Notebooks.

## Architecture & Pipeline
- **Data Loading**: Reads tabular data (`train.csv`, `test.csv`).
- **Cost / Loss Function**: Implements Mean Squared Error (MSE) loss computation.
- **Optimization**: Gradient descent algorithm updating model weights and bias iteratively over epochs.
- **Evaluation**: Computes test error and visualizes the fitted regression line against data points.

## Data
- **Dataset**: Tabular training and testing datasets (`train.csv`, `test.csv`) with continuous features (`x`, `y`).

## Method & Algorithms
- **Gradient Descent**: Iterative parameter optimization minimizing residual sum of squares.

## Verified Results & Metrics
- Successfully fitted linear regression models to dataset points, evaluated test errors, and generated regression line visualizations.

## Limitations & Caveats
- Basic educational implementation for linear regression fundamentals.

## Run Instructions
```bash
jupyter notebook linearRegression.ipynb
```

## CV Bullet Points
- Implemented linear regression from scratch with gradient descent optimization and cost function evaluation in Python.
- Visualized data distributions and fitted regression lines to evaluate model generalization on test datasets.

## Claims to Avoid
- Do not claim advanced regression techniques beyond standard gradient descent.
