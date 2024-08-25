# Policy Gradient Methods

## Overview
Policy Gradient methods optimize the policy directly rather than the value function. They are particularly useful in high-dimensional action spaces and continuous action spaces.

## Where is it Used?
- **Robotics:** For controlling complex robotic actions.
- **Game AI:** For real-time decision making in complex games.

## How Does it Work?
These methods maximize the expected reward by updating the policy's parameters in the direction that increases rewards. The gradient ascent approach is used:
\[ \theta_{t+1} = \theta_t + \alpha \nabla_\theta J(\theta) \]
Where \( J(\theta) \) is the expected return.
