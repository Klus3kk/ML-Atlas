# MAE (Mean Absolute Error)

## Overview

Mean Absolute Error (MAE) measures the average magnitude of errors between predicted and actual values. Unlike RMSE, MAE is not sensitive to outliers and provides a more balanced view of the errors.

## Where is it Used?

- **Regression Models:** Evaluates how well the model predicts continuous outcomes.
- **Error Analysis:** Offers insights into the average error magnitude without being skewed by outliers.
- **Model Comparison:** Helps in comparing the performance of different regression models.

## How Does it Work?

MAE is calculated as follows:
\[ \text{MAE} = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y}_i| \]

Where:
- \( y_i \) is the actual value.
- \( \hat{y}_i \) is the predicted value.
- \( n \) is the number of observations.
