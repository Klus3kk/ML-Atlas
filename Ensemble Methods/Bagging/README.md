# Bagging

## Overview

Bagging, short for Bootstrap Aggregating, is an ensemble technique that improves the stability and accuracy of machine learning algorithms by training multiple versions of a model on different subsets of the training data and averaging their predictions.

## Where is it Used?

- **Decision Trees:** Random Forests are a popular implementation of bagging applied to decision trees.
- **Variance Reduction:** Effective when reducing variance in high-variance models like decision trees.
- **Classification and Regression Tasks:** Applied to a variety of models to improve performance.

## How Does it Work?

Bagging involves generating multiple bootstrap samples from the original dataset (sampling with replacement). Each sample is used to train a separate model. The final prediction is made by averaging the predictions (for regression) or by majority voting (for classification).
