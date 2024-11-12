# Reinforcement Learning

This site is dedicated to all things reinforcement learning (RL). Here, you'll find a collection of essential resources including papers, talks, and lectures that cover a wide range of RL concepts and advancements. My goal is to create a comprehensive learning repository for anyone interested in reinforcement learning.

## Topics

* Value-based RL
  * Markov Decision Processes (MDPs): The foundational framework for RL, including states, actions, rewards, and transitions.
  * Q-learning: A model-free value-based method for learning action-value functions.
  * Model-based RL: Techniques that assume a known model or learn a model of the environment.
    * Value Iteration and Policy Iteration: Dynamic programming methods that use Bellman equations to compute optimal policies, typically under a known environment model.
* Model-free RL:
  * Policy gradient methods [info](./policygradients.html)
    * REINFORCE
    * Actor-Critic Methods
      * DDPG (Deep Deterministic Policy Gradient)
      * Advanced policy gradient methods (TRPO, PPO)
  * Deep reinforcement learning [info](./deeprl.html)
    * Deep Q Networks 
* Inverse reinforcement learning: Methods that infer the reward function from observed behavior, allowing agents to learn by imitation
* Reinforcement learning with human feedback (RLHF) [info](./rlhf.html)
* Evolutionary reinforcement learning [info](./evolution.html)

## Papers

### Policy Gradient Methods

More information on policy gradient methods [here](./policygradients.html)

* Proximal Policy Optimization Algorithms (Schulman et al. 2017) [link](https://arxiv.org/pdf/1707.06347)
* Trust Region Policy Optimization (Schulman et al. 2015) [link](https://arxiv.org/abs/1502.05477)
* Algorithms for Inverse Reinforcement Learning (Ng and Russell 2000) [link](https://ai.stanford.edu/~ang/papers/icml00-irl.pdf) 
* Asynchronous Methods for Deep Reinforcement Learning (A2C) (Mnih et al. 2016) [link](https://arxiv.org/pdf/1602.01783) 
* A3C (Mnih et al. 2016) [link](https://arxiv.org/pdf/1602.01783v2)
* R^2: Fast Reinforcement Learning via Slow Reinforcement Learning (Duan et al. 2016) [link](https://arxiv.org/pdf/1611.02779)
* Policy Gradient Methods for Reinforcement Learning with Function Approximation (Sutton et al. 1999) [link](https://proceedings.neurips.cc/paper_files/paper/1999/file/464d828b85b0bed98e80ade0a5c43b0f-Paper.pdf)
* High-Dimensional Continuous Control Using Generalized Advantage Estimation (Schulman et al. 2018) [link](https://arxiv.org/pdf/1506.02438)
* Equivalence Between Policy Gradients and Soft Q-Learning (Schulman et al. 2016) [link](https://arxiv.org/pdf/1704.06440)
* More to be added

### Deep Reinforcement Learning

More information on deep RL [here](./deeprl.html)

* #Exploration: A Study of Count-Based Exploration for Deep Reinforcement Learning [link](https://arxiv.org/pdf/1611.04717) 
* Benchmarking Deep Reinforcement Learning for Continuous Control [link](https://arxiv.org/pdf/1604.06778) / [code](https://github.com/rll/rllab)
* MuJoCo: A physics engine for model-based control [link](https://homes.cs.washington.edu/~todorov/papers/TodorovIROS12.pdf)

### Evolutionary Reinforcement Learning 

More information on evolution [here](./evolution.html)

* Evolution Strategies as a Scalable Alternative to Reinforcement Learning by OpenAI (September 2017) [link](https://arxiv.org/pdf/1703.03864)
* Deep Neuroevolution: Genetic Algorithms are a Competitive Alternative for Training Deep Neural Networks for Reinforcement Learning by Uber (first paper, April 2018) [link](https://arxiv.org/pdf/1712.06567) 
* Improving Exploration in Evolution Strategies for Deep Reinforcement Learning via a Population of Novelty-Seeking Agents by Uber (second paper, October 2018) [link](https://arxiv.org/pdf/1712.06560)

### Reinforcement Learning with Human Feedback (RLHF)

More information on RLHF [here](./rlhf.html)

* Training language models to follow instructions with human feedback (Ouyang et al. 2022) [paper](https://arxiv.org/abs/2203.02155)
* Learning to summarize from human feedback (Stiennon et al. 2020) [paper](https://arxiv.org/abs/2009.01325)
* Deep Reinforcement Learning from Human Preferences (Christiano et al. 2023) [paper](https://arxiv.org/pdf/1706.03741)

### Adversarial RL

TO BE ADDED

## Resources

### Background
* David Silver's Reinforcement Learning Course [website](https://www.davidsilver.uk/teaching/)
* DeepRL Bootcamp [website](https://sites.google.com/view/deep-rl-bootcamp)
* Pieter Abbeel's Foundations of DeepRL series [playlist](https://www.youtube.com/watch?v=2GwBez0D20A)
* John Schulman's "Deep Reinforcement Learning via Policy Optimization" [lecture](http://joschu.net/docs/2017-rldm.pdf) (2017)
* John Schulman's RLHF [lecture](https://www.youtube.com/watch?v=hhiLw5Q_UFg) (2023)
* Abbeel's Inverse RL [lecture](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa12/slides/inverseRL.pdf) 

### Recent Advances in RL
* ICML "Reinforcement Learning at the Hyperscale" [talk](https://slideslive.com/39022179/reinforcement-learning-at-the-hyperscale) (2024)
* JaxRL [code](https://github.com/ikostrikov/jaxrl)
* JaxMARL [paper](https://arxiv.org/abs/2311.10090) / [code](https://github.com/ikostrikov/jaxrl)
* Uber Deep Neuroevolution [code](https://github.com/uber-research/deep-neuroevolution?uclick_id=b2d35630-373d-4a27-b230-9268a32455b5)

