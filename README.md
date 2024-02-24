
# Salary Prediction

### Overview

This repository contains code for predicting salaries based on position levels using two different regression models: Simple Linear Regression and Polynomial Regression. The dataset consists of information about different positions, their corresponding levels, and the associated salaries.

### Dataset

The dataset used for this project includes three columns:

- Position: The job position/title.
- Level: The level associated with the position.
- Salary: The corresponding salary for the given position and level.

| Position          | Level | Salary    |
|-------------------|-------|-----------|
| Business Analyst  | 1     | 45000     |
| Junior Consultant | 2     | 50000     |
| Senior Consultant | 3     | 60000     |
| Manager           | 4     | 80000     |
| Country Manager   | 5     | 110000    |
| Region Manager    | 6     | 150000    |
| Partner           | 7     | 200000    |
| Senior Partner    | 8     | 300000    |
| C-level           | 9     | 500000    |
| CEO               | 10    | 1000000   |


### Code Structure

The code is organized into two main files:

1. SimpleLinearRegression.py: This script implements the Simple Linear Regression model to predict salaries based on the level of the position.

2. PolynomialRegression.py: This script implements Polynomial Regression to capture more complex relationships between position levels and salaries.

### Results

The output of each script will include visualizations of the regression models fitted to the dataset. The Simple Linear Regression model will provide a straight line fit, while the Polynomial Regression model will capture more complex relationships with a curved fit.

### Interpretation

The predicted salary values can be interpreted as estimations based on the trained models. It's important to note that these predictions are based on the patterns observed in the provided dataset and may not perfectly generalize to new data.

### Conclusion

This project demonstrates the application of two regression models to predict salaries based on position levels. Users can choose between the Simple Linear Regression model for a basic understanding of the relationship or the Polynomial Regression model for capturing more complex patterns.
