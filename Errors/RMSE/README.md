# RMSE (Root Mean Squared Error)

## Overview

Root Mean Squared Error (RMSE) measures the average magnitude of errors between predicted and actual values. It gives a sense of how spread out the residuals (errors) are. RMSE is sensitive to outliers and provides a more significant penalty for large errors.

## Where is it Used?

- **Regression Models:** Assesses how well the model predicts continuous outcomes.
- **Model Comparison:** Helps in comparing the performance of different regression models.
- **Error Analysis:** Provides insight into the magnitude of prediction errors.

## How Does it Work?

RMSE is calculated as follows:
\[ \text{RMSE} = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2} \]

Where:
- \( y_i \) is the actual value.
- \( \hat{y}_i \) is the predicted value.
- \( n \) is the number of observations.
