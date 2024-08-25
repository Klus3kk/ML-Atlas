# Boosting

## Overview

Boosting is an ensemble technique that combines multiple weak learners (models that perform slightly better than random chance) to create a strong learner. It focuses on correcting the errors made by previous models in the sequence.

## Where is it Used?

- **Classification and Regression Tasks:** Commonly used for improving the performance of decision trees.
- **Reducing Bias:** Effective in reducing bias and improving the accuracy of models.
- **Widely Used Algorithms:** AdaBoost, Gradient Boosting, and XGBoost.

## How Does it Work?

Boosting works by sequentially training models, with each new model attempting to correct the errors of the previous ones. The models are trained using a weighted dataset where misclassified data points are given higher importance.
