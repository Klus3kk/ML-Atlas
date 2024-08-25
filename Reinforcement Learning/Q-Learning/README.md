# Q-Learning

## Overview
Q-Learning is an off-policy algorithm that learns the value of actions in states. It seeks to find the optimal action-selection policy by maximizing the total reward over time. 

## Where is it Used?
- **Game AI:** To train agents that play games like chess or video games.
- **Robotics:** For decision-making in dynamic environments.

## How Does it Work?
Q-Learning uses a Q-table to store the value (Q-value) of each action in a state. It updates the Q-values using the Bellman equation:
\[ Q(s, a) = Q(s, a) + \alpha \left[ r + \gamma \max_a Q(s', a) - Q(s, a) \right] \]
Where:
- \( s \) is the current state.
- \( a \) is the action taken.
- \( r \) is the reward received.
- \( \alpha \) is the learning rate.
- \( \gamma \) is the discount factor.
- \( s' \) is the next state.
