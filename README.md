# Regression Methods Project

## Overview

This project investigates the performance of two regression techniques: **Gradient Descent** and **Coordinate Descent**. It aims to analyze the effectiveness of these methods in predicting outcomes based on a dataset with multiple features. 

## Goals

- Implement and compare the results of gradient descent and coordinate descent for Lasso regression.
- Visualize the predictions against actual values to evaluate the performance of the models.
- Analyze the impact of the regularization parameter on the regression coefficients.

## Methodology

1. **Data Preparation**
   - The dataset was divided into training and testing sets, ensuring a proper split to evaluate model performance.
   - Features were standardized to improve the efficiency and effectiveness of the regression algorithms.

2. **Gradient Descent Implementation**
   - A custom function was developed to perform gradient descent, minimizing the loss function with respect to the coefficients.
   - Predictions were generated for both the training and test datasets, and results were visualized.

3. **Coordinate Descent Implementation**
   - A separate function was created to implement the coordinate descent algorithm for Lasso regression, utilizing the same dataset.
   - Predictions were also generated and visualized for this method.

4. **Visualization**
   - Plots were generated to compare the true values against the predicted values for both methods, allowing for visual assessment of model performance.

5. **Parameter Comparison**
   - The coefficients from both methods were compared to assess the similarity and effectiveness of the algorithms.
   - Root Mean Square Error (RMSE) was calculated to quantify the prediction errors for both training and test datasets.

## Results

- The visualizations (included as figures) show that both models follow the data trends closely, indicating a good fit.
- The coefficients obtained from coordinate descent were sparse, confirming the regularization effect of Lasso regression.
- Performance metrics (RMSE values) were similar across both methods, demonstrating that both approaches effectively minimized prediction errors.

## Conclusion

Both gradient descent and coordinate descent yielded satisfactory results in predicting outcomes based on the dataset. The coordinate descent method, in particular, highlighted the advantages of Lasso regression in achieving sparsity in coefficients.
