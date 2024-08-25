# Adam Optimizer

## Overview

Adam (Adaptive Moment Estimation) is an advanced optimization algorithm that combines the benefits of two other extensions of stochastic gradient descent: AdaGrad and RMSprop. It maintains a running average of both the gradient and its square, allowing for an adaptive learning rate.

## Where is it Used?

- **Deep Learning:** Widely used for training deep neural networks.
- **Complex Models:** Effective for models with sparse gradients or noisy objectives.
- **Efficient Convergence:** Suitable for large-scale problems with vast amounts of data or parameters.

## How Does it Work?

Adam calculates adaptive learning rates for each parameter by keeping an exponentially decaying average of past gradients and squared gradients. This makes it particularly effective for problems with noisy gradients or where the learning rate needs fine-tuning.

The update rules are:
\[ m_t = \beta_1 m_{t-1} + (1 - \beta_1) \nabla_\theta J(\theta) \]
\[ v_t = \beta_2 v_{t-1} + (1 - \beta_2) (\nabla_\theta J(\theta))^2 \]
\[ \theta := \theta - \alpha \frac{m_t}{\sqrt{v_t} + \epsilon} \]

Where:
- \( m_t \) and \( v_t \) are the moving averages of the gradient and the squared gradient, respectively.
- \( \beta_1 \) and \( \beta_2 \) are decay rates.
- \( \epsilon \) is a small constant for numerical stability.
