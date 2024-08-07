# Linear Regression with Gradient Descent

## Overview

This project demonstrates a simple implementation of linear regression using gradient descent in Python. The goal is to fit a line to a set of data points to predict values and evaluate the model's performance.

## Project Structure

- `linearRegression.ipynb`: Jupyter notebook containing the code for the linear regression model.
- `train.csv`: CSV file containing training data with columns `x` and `y`.
- `test.csv`: CSV file containing test data with columns `x` and `y`.

## Files Description

### `linearRegression.ipynb`

This Jupyter notebook includes:
1. **Loading Data**: Reads the training data from `train.csv`.
2. **Data Visualization**: Plots the data points to visualize the distribution.
3. **Loss Function**: Implements a loss function to calculate the error between predicted and actual values.
4. **Gradient Descent**: Uses gradient descent to optimize the parameters of the linear regression model.
5. **Model Training**: Trains the model over a specified number of epochs.
6. **Model Evaluation**: Tests the model on test data and calculates the total error.
7. **Results Visualization**: Plots the data points and the fitted regression line.

### `train.csv`

Contains training data with the following columns:
- `x`: Feature values
- `y`: Target values

### `test.csv`

Contains test data with the following columns:
- `x`: Feature values
- `y`: Target values

## How to Run

1. **Set Up Environment**:
   - Ensure you have Python installed.
   - Install necessary packages using pip:
     ```bash
     pip install pandas matplotlib
     ```

2. **Run the Notebook**:
   - Open `linearRegression.ipynb` in Jupyter Notebook or JupyterLab.
   - Execute each cell to run the analysis.

## Results

The notebook performs linear regression using gradient descent to fit a line to the data points. It provides visualizations of the data, the fitted line, and calculates the model's performance on test data.
![image](https://github.com/user-attachments/assets/b6d80f91-fc5c-4bbd-8076-77d4ad308981)


## License

This project is licensed under the MIT License.
