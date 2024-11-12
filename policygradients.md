# Policy Gradient Methods

Policy gradient methods are a class of algorithms in reinforcement learning that aim to optimize the policy directly by following the gradient of expected rewards with respect to the policy parameters. 

## Actor-Critic Methods

* Combine the strengths of both policy-based (actor) and value-based (critic) approaches
* Directly optimize the policy while reducing the high variance typically associated with policy gradient methods
* Critic helps reduce this variance by evaluating state values and providing feedback to the actor, which is responsible for adjusting the policy by updating policy parameters

## Advanced Policy Gradient Methods: TRPO/PPO

### TRPO

* Ensures policy updates are within a trust region to maintain stable learning
* TRPO uses KL divergence as a measure of the difference between the old policy and the new policy

### PPO

* Uses a clipped surrogate objective to avoid large policy updates
* Reduces TRPO's constrained optimization problem to an unconstrained optimization problem 
