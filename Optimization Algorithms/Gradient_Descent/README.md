# Gradient Descent

## Overview

Gradient Descent is the most common optimization algorithm used to minimize the loss function in machine learning models. It works by iteratively moving towards the minimum of a function using the gradient, which indicates the direction of the steepest ascent.

## Where is it Used?

- **Training Neural Networks:** Used extensively to minimize the loss in deep learning models.
- **Linear and Logistic Regression:** Helps find the best-fitting line or decision boundary.
- **Convex Optimization Problems:** Typically applied where the loss function is convex.

## How Does it Work?

Gradient Descent updates the model's parameters by taking steps proportional to the negative of the gradient of the loss function concerning those parameters. The learning rate determines the size of these steps.

The update rule is given by:
\[ \theta := \theta - \alpha \nabla_\theta J(\theta) \]

Where:
- \( \theta \) is the parameter vector.
- \( \alpha \) is the learning rate.
- \( \nabla_\theta J(\theta) \) is the gradient of the loss function.
