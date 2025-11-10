📘 Nonlinear Curve Fitting using Least Squares Optimization
Overview

This project performs parameter estimation for a nonlinear model using least squares optimization. The goal is to find the optimal parameters that best fit experimental or simulated data points stored in a CSV file (xy_data.csv).

The model relates two datasets (x, y) with a mathematical expression involving trigonometric and exponential components. The optimization adjusts parameters such as θ (theta), M, and X to minimize the difference between the model predictions and observed data.

🚀 Features

Loads input data (x, y) from a CSV file using Pandas.

Defines a nonlinear model with trigonometric and exponential terms.

Uses SciPy’s least_squares optimization to estimate the best-fitting parameters.

Computes residuals between predicted and actual data to guide optimization.

Visualizes the fitted curve with Matplotlib for result comparison.

⚙️ Model Equation

For parameters (θ, M, X) and time variable t, the model is defined as:

<img width="423" height="66" alt="image" src="https://github.com/user-attachments/assets/72491eba-9b4c-43fd-b4e8-8cb058af126b" />

where θ_rad = radians(θ).
