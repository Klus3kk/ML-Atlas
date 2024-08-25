# Actor-Critic Methods

## Overview
Actor-Critic methods combine the benefits of both policy gradient (actor) and value-based (critic) methods. The actor updates the policy, while the critic evaluates the action taken by the actor.

## Where is it Used?
- **Autonomous driving:** For real-time decision making.
- **Robotics:** For tasks requiring both value estimation and action policy.

## How Does it Work?
The actor updates the policy parameters in the direction suggested by the critic. The critic estimates the value function, guiding the actor.
