# AdaBoost

## Overview
AdaBoost, short for Adaptive Boosting, is an ensemble learning method that combines multiple weak classifiers to create a strong classifier. It adjusts the weights of incorrectly classified instances, making them more important in subsequent models.

### Where is it Used?
- **Face detection:** Widely used in the Viola-Jones face detection algorithm.
- **Text classification:** Identifying the topic of articles or documents.
- **Fraud detection:** Classifying transactions as fraudulent or legitimate.

## How Does it Work?
AdaBoost works by training a sequence of weak learners, typically decision stumps. After each round, it increases the weight of misclassified instances and decreases the weight of correctly classified ones, forcing the model to focus on difficult cases.
