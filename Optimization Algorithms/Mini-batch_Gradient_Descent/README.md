# Mini-batch Gradient Descent

## Overview

Mini-batch Gradient Descent is a compromise between standard gradient descent and stochastic gradient descent. It computes the gradient using small batches of data, balancing efficiency and performance.

## Where is it Used?

- **Training Deep Learning Models:** Commonly used in deep learning due to its balance between speed and convergence stability.
- **Large Datasets:** Suitable for large datasets where full-batch gradient descent is impractical.
- **Improved Convergence:** Helps in smoother convergence compared to SGD.

## How Does it Work?

Mini-batch Gradient Descent divides the training data into small batches and performs an update for each batch. This approach reduces the variance in parameter updates and often leads to faster convergence compared to SGD.

The update rule is:
\[ \theta := \theta - \alpha \nabla_\theta J(\theta; X^{(i:i+n)}, y^{(i:i+n)}) \]

Where \( (X^{(i:i+n)}, y^{(i:i+n)}) \) is a mini-batch of the training set.
