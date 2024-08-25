### Stochastic Gradient Descent (SGD)

#### Overview

Stochastic Gradient Descent (SGD) is a variation of gradient descent where the gradient is computed using a single randomly selected data point (or a small batch) instead of the entire dataset. This makes it faster and suitable for large datasets.

#### Where is it Used?

- **Online Learning:** Models that update in real-time as new data arrives.
- **Large Datasets:** Efficient when working with massive datasets where standard gradient descent is too slow.
- **Deep Learning:** Often used with large-scale neural networks.

#### How Does it Work?

SGD approximates the gradient using a single data point or a small batch, which introduces noise into the updates. This noise can help escape local minima but also requires careful tuning of the learning rate.

The update rule is:
\[ \theta := \theta - \alpha \nabla_\theta J(\theta; x^{(i)}, y^{(i)}) \]

Where \( (x^{(i)}, y^{(i)}) \) is a single training example.
