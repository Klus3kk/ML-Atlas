# RMSprop

## Overview

RMSprop (Root Mean Square Propagation) is an optimization algorithm that adjusts the learning rate for each parameter adaptively. It addresses the issue of AdaGrad's rapidly decreasing learning rate by maintaining a moving average of the squared gradient.

## Where is it Used?

- **Recurrent Neural Networks:** Particularly effective in training RNNs.
- **Deep Learning:** Used to train models with noisy objectives or sparse gradients.
- **Training Stability:** Helps stabilize training by adjusting the learning rate based on recent gradients.

## How Does it Work?

RMSprop updates the learning rate for each parameter by dividing the learning rate by the square root of the average of the recent gradients. This prevents the learning rate from becoming too small, allowing for more consistent updates.

The update rule is:
\[ v_t = \beta v_{t-1} + (1 - \beta) (\nabla_\theta J(\theta))^2 \]
\[ \theta := \theta - \alpha \frac{\nabla_\theta J(\theta)}{\sqrt{v_t} + \epsilon} \]

Where:
- \( v_t \) is the moving average of the squared gradient.
- \( \beta \) is the decay rate.
- \( \epsilon \) is a small constant for numerical stability.
