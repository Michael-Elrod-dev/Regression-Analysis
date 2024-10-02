# Regression-Analysis

This project explores various regression techniques using the Boston Housing dataset. It implements and compares linear regression, polynomial regression, and ridge regression models.

## Dataset

The Boston Housing dataset contains 506 samples with 13 feature variables and 1 target variable (median house price). The dataset is split into training (300 samples) and test sets.

## Features

1. Linear Regression with Varying Training Set Sizes
   - Implements linear regression with different training set sizes
   - Plots Mean Squared Error (MSE) vs. training set size

2. Polynomial Feature Expansion
   - Expands features to higher-order terms (up to degree 6)
   - Compares model performance across different polynomial degrees

3. Ridge Regression
   - Implements ridge regression with various regularization strengths
   - Analyzes the effect of regularization on model performance

## Files

- `main.py`: Main script containing all implementations and visualizations
- `housing.data`: Boston Housing dataset
- `images/`: Directory containing all generated plots

## Requirements

- Python 3.x
- NumPy
- pandas
- matplotlib
- scikit-learn

## Usage

1. Ensure all required libraries are installed
2. Place the `housing.data` file in the `files/` directory
3. Run each cell sequentially to replicate displayed results

## Results

The script generates several plots:

1. `linear_regression.png`: MSE vs. Training Set Size
2. `MSEvsPoly.png`: MSE vs. Polynomial Degree
3. `MSEvsRidge.png`: MSE vs. log10(lambda) for Ridge Regression

Each plot is accompanied by an explanation of the observed trends in the code comments.

## Conclusion

This project demonstrates the trade-offs between model complexity and generalization in regression analysis. It highlights the importance of choosing appropriate model complexity and regularization to balance between underfitting and overfitting.