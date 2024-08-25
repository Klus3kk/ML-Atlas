# AdaGrad

## Overview

AdaGrad (Adaptive Gradient Algorithm) is an optimization algorithm that adapts the learning rate based on the history of gradients. It is particularly useful for dealing with sparse data or features, where some parameters require more frequent updates than others.

## Where is it Used?

- **Sparse Data:** Ideal for problems where data or features are sparse, such as text or image recognition.
- **Online Learning:** Can be applied in online learning scenarios due to its adaptive nature.
- **Deep Learning:** Used in scenarios where different features require different learning rates.

## How Does it Work?

AdaGrad modifies the learning rate for each parameter based on the sum of all historical squared gradients. This means that parameters with large gradients are updated more slowly than those with small gradients.

The update rule is:
\[ \theta := \theta - \frac{\alpha}{\sqrt{G_{t,ii}} + \epsilon} \nabla_\theta J(\theta) \]

Where:
- \( G_{t,ii} \) is the sum of the squares of the gradients with respect to \( \theta_i \) up to time \( t \).
- \( \epsilon \) is a small constant to prevent division by zero.
