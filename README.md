Heart Rate Recovery Analysis using Polynomial Regression

Introduction
In this project, we analyze Heart Rate Recovery (HRR) after exercise using Fitbit fitness tracker data (heartrate_seconds_merged.csv). The goal is to apply a Polynomial Regression model to fit the non-linear recovery trend and test how different optimization algorithms perform in terms of convergence and accuracy.

Dataset
Source: Fitbit Fitness Tracker Data (heartrate_seconds_merged.csv)

Target Variable (y): Heart Rate values

Feature (x): Scaled time sequence

Model: Polynomial Regression (Degree = 3)

Implemented Optimization Algorithms
We implemented and compared five optimization methods from scratch:

Gradient Descent (GD): Uses the whole dataset in each epoch for a stable update path.

Stochastic Gradient Descent (SGD): Updates weights using a single random sample per iteration, introducing natural fluctuations.

Mini-Batch Gradient Descent: Balances between GD and SGD by processing small batches of data for smoother convergence.

RMSprop: Adapts the learning rate individually for each parameter using a moving average of squared gradients.

Adam (Adaptive Moment Estimation): Combines momentum and adaptive learning rates, providing the most efficient and stable convergence among all tested optimizers.

Repository Structure
1_Polynomial_Regression_GD.ipynb: Gradient Descent implementation.

2_Polynomial_Regression_SGD.ipynb: Stochastic Gradient Descent implementation.

3_Polynomial_Regression_MiniBatch.ipynb: Mini-Batch Gradient Descent implementation.

4_Polynomial_Regression_RMSprop.ipynb: RMSprop optimizer implementation.

5_Polynomial_Regression_Adam.ipynb: Adam optimizer implementation.# Heart-Rate-Polynomial-Optimizers
