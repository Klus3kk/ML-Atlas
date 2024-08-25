# SARSA

## Overview
SARSA (State-Action-Reward-State-Action) is an on-policy RL algorithm that updates the Q-value based on the action actually taken by the current policy.

## Where is it Used?
- **Robotics:** In scenarios requiring adherence to a specific policy.
- **Pathfinding:** For finding the optimal path under specific rules.

## How Does it Work?
The Q-value is updated using the following equation:
\[ Q(s, a) = Q(s, a) + \alpha \left[ r + \gamma Q(s', a') - Q(s, a) \right] \]
Where \( s' \) and \( a' \) are the next state and action taken by the policy.
