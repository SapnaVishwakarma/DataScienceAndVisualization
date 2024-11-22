# Data Science and Visualization (DSV) Assignments

This repository contains the assignments for the Data Science and Visualization course. The assignments include dataset exploration, data splitting, and linear regression modeling.

## Introduction

These assignments focus on:
1. Exploring and analyzing the Iris dataset.
2. Splitting datasets into training and testing sets.
3. Fitting and evaluating a linear regression model using a custom dataset.

## Main Tasks

### 1. Dataset Exploration

- **Task**: Load the Iris dataset from `sklearn.datasets` and perform an initial exploration.
- **Subtasks**:
  - Load the Iris dataset.
  - Display the first five rows of the dataset.
  - Print the dataset’s shape.
  - Calculate and display summary statistics (mean, standard deviation, min/max values) for each feature.

### 2. Data Splitting

- **Task**: Split the Iris dataset into training and testing sets using an 80-20 split.
- **Subtasks**:
  - Split the dataset into training and testing sets.
  - Print the number of samples in both the training and testing sets.
  - Visualize the data split using bar charts.

### 3. Linear Regression

- **Task**: Use a dataset with the features `YearsExperience` and `Salary` to fit and evaluate a linear regression model.
- **Subtasks**:
  - Create or load a dataset with `YearsExperience` and `Salary`.
  - Split the dataset into training and testing sets.
  - Fit a linear regression model to predict `Salary` based on `YearsExperience`.
  - Evaluate the model's performance using Mean Squared Error (MSE) on the test set.
  - Visualize the regression line and data points.

## Challenges

### Dataset Exploration
- **Challenge**: Ensuring the accuracy of summary statistics for the dataset's features.
- **Solution**: Used `pandas` library for accurate and efficient calculation of statistics.

### Data Splitting
- **Challenge**: Maintaining the integrity of the dataset during the splitting process.
- **Solution**: Utilized `train_test_split` from `sklearn.model_selection` to ensure an 80-20 split and reproducibility with a fixed random state.

### Linear Regression
- **Challenge**: Accurately predicting `Salary` based on `YearsExperience` and evaluating model performance.
- **Solution**: Applied `LinearRegression` from `sklearn.linear_model` and used Mean Squared Error (MSE) for performance evaluation.

## Experience

Working on these assignments provided valuable insights into the process of data exploration, splitting, and linear regression modeling. Key takeaways include:
- The importance of thorough data exploration to understand the dataset.
- The significance of proper data splitting to ensure fair model evaluation.
- The practical application of linear regression to predict outcomes and evaluate model performance.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/DSV-Assignments.git
