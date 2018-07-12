# Deep_Reinforcement_Learning
Deep Reinforcement Learning (C++, Python) (Windows, Mac, Ubuntu) (TensorFlow) (2018)
![Farshid](https://github.com/pirahansiah/Deep_Reinforcement_Learning/blob/master/4.jpg)
# Deep Reinforcement Learning (C++, Python) (Windows, Mac, Ubuntu) (TensorFlow) (2018)
## Reinforcement Learning Methods
- Dynamic Programming (DP) [89]
- Monte Carlo [94]
- Temporal-Difference [88]
- Q-Learning (Off-policy TD algorithm) [89]
- Sarsa (On-policy TD algorithm) [94]
- R-Learning (learning of relative values) [93]
- Function Approximation methods (Least-Square Temporal Difference, Least-Square Policy Iteration) [96]
- Policy Search / Policy Gradient [99]
- Hierarchical RL [99]
- Deep Learning + Reinforcement Learning [2014]
- DQN: A reinforcement learning algorithm that combines Q-Learning with deep neural networks to let RL work for complex, high-dimensional environments, like video games, or robotics.
- Double Q Learning: Corrects the stock DQN algorithm’s tendency to sometimes overestimate the values tied to specific actions.
- Prioritized Replay: Extends DQN’s experience replay function by learning to replay memories where the real reward significantly diverges from the expected reward, letting the agent adjust itself in response to developing incorrect assumptions.
- Dueling DQN: Splits the neural network into two — one learns to provide an estimate of the value at every time step, and the other calculates potential advantages of each action, and the two are combined for a single action-advantage Q function.
- 
- 
- Action-Selection Strategies for Exploration
- Partially Observable Markov Decision Processes (POMDPs)
- Deep Recurrent Q-Networks (DRQN)
- Double-Dueling-DQN: The goal of Dueling DQN is to have a network that separately computes the advantage and value functions, and combines them back into a single Q-function only at the final layer
- Asynchronous Advantage Actor-Critic (A3C) algorithm: universal starter agent, 
