# Deep Reinforcement Learning

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](https://python.org)
[![C++](https://img.shields.io/badge/C%2B%2B-17-blue)](https://isocpp.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white)](https://tensorflow.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Deep Reinforcement Learning (C++, Python) — From classical methods to modern foundation models.

<img src="https://github.com/pirahansiah/Deep_Reinforcement_Learning/blob/master/4.jpg" width="200" height="100">

## Overview

A comprehensive exploration of Deep Reinforcement Learning methods, from foundational algorithms (Q-Learning, Policy Gradient) to cutting-edge approaches (model-based RL, offline RL, foundation agents).

## Classical RL Methods

| Method | Type | Key Idea | Year |
|--------|------|----------|------|
| **Dynamic Programming** | Model-based | Value/Policy iteration with known dynamics | 1989 |
| **Monte Carlo** | Model-free | Learn from complete episode returns | 1994 |
| **Temporal-Difference** | Model-free | Learn from bootstrapped estimates | 1988 |
| **Q-Learning** | Off-policy TD | Learn action-value function | 1989 |
| **SARSA** | On-policy TD | Learn while following policy | 1994 |
| **R-Learning** | Relative values | Learn relative reward values | 1993 |
| **Policy Gradient** | Direct policy | Optimize policy directly via gradient | 1999 |
| **Hierarchical RL** | Multi-level | Decompose tasks into subgoals | 1999 |

## Deep RL Methods

| Algorithm | Key Innovation | Use Case |
|-----------|---------------|----------|
| **DQN** | Neural network for Q-value estimation | Atari games, discrete control |
| **Double DQN** | Decouples selection from evaluation | Reduces Q-value overestimation |
| **Prioritized Experience Replay** | Non-uniform replay sampling | Better sample efficiency |
| **Dueling DQN** | Separate value/advantage streams | Better state-value estimation |
| **A3C** | Asynchronous parallel actors | Continuous/discrete control |
| **DDPG** | Actor-critic for continuous actions | Robotics, control |
| **TD3** | Twin delayed DDPG | Improved DDPG stability |
| **SAC** | Maximum entropy RL | Robust exploration |
| **PPO** | Clipped surrogate objective | Stable policy optimization |
| **IMPALA** | Distributed importance-weighted actor | Large-scale training |

## Modern Deep RL (2025-2026 SOTA)

### Model-Based RL

| Method | Description | Key Advantage |
|--------|-------------|---------------|
| **Dreamer V3** | World model for continuous control | Sample efficiency, generalization |
| **IRIS** | Token-based world model | Scalable imagination |
| **DIAMOND** | Diffusion world models | High-fidelity planning |
| **LeCun's JEPA** | Joint Embedding Predictive Architecture | Understanding without generation |

### Foundation Agents (2025-2026)

| Agent | Description | Key Innovation |
|-------|-------------|----------------|
| **UniSim** | Universal simulator for real-world interaction | Learned environment models |
| **RT-2** | Robotics Transformer 2 | Vision-language-action models |
| **GR-2** | World model for robot generation | Video prediction for manipulation |
| **V-JEPA 2** | Video Joint Embedding Predictive Architecture | Self-supervised video understanding |
| **Octo** | Generalist robot policy | Open-source robot foundation model |
| **OpenVLA** | Open-source vision-language-action model | 7B parameter robot foundation model |

### Offline RL

| Method | Description | Key Innovation |
|--------|-------------|----------------|
| **Decision Transformer** | Sequence modeling for RL | Treats RL as sequence prediction |
| **Decision Diffuser** | Diffusion models for planning | Generative trajectory optimization |
| **IQL** | Implicit Q-Learning | No OOD actions |
| **TD3+BC** | Simple offline RL baseline | Strong performance with minimal code |

### Multi-Agent RL

| Method | Description | Key Innovation |
|--------|-------------|----------------|
| **MAPPO** | Multi-Agent PPO | Scalable multi-agent training |
| **QMIX** | Monotonic value factorization | Decentralized execution |
| **MADDPG** | Multi-Agent DDPG | Centralized training, decentralized execution |
| **Self-Play** | AlphaStar, OpenAI Five | Competitive multi-agent training |

### RLHF & Alignment

| Method | Description | Key Innovation |
|--------|-------------|----------------|
| **PPO** | Proximal Policy Optimization | Used in ChatGPT/GPT-4 alignment |
| **DPO** | Direct Preference Optimization | Simplifies RLHF pipeline |
| **KTO** | Kahneman-Tversky Optimization | Human feedback without pairwise preferences |
| **ORPO** | Odds Ratio Preference Optimization | Alignment without reference model |

## Modern RL Frameworks (2025-2026)

- **[Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3)** — Reliable RL implementations in PyTorch
- **[CleanRL](https://github.com/vwxyzjn/cleanrl)** — Single-file implementations of RL algorithms
- **[RLlib](https://docs.rllib.io/)** — Scalable RL library from Ray
- **[Tianshou](https://github.com/thu-ml/tianshou)** — High-performance RL library
- **[D3RLPy](https://github.com/takuseno/d3rlpy)** — Offline RL library
- **[Gymnasium](https://gymnasium.farama.org/)** — Standard RL environments (successor to OpenAI Gym)
- **[MuJoCo](https://mujoco.org/)** — Physics engine for continuous control
- **[Isaac Lab](https://isaac-sim.github.io/IsaacLab/)** — NVIDIA's robot learning framework
- **[PettingZoo](https://pettingzoo.farama.org/)** — Multi-agent RL environments

## Applications

- **Robotics** — Manipulation, locomotion, autonomous navigation
- **Game AI** — StarCraft II, Dota 2, chess engines
- **Autonomous Driving** — Self-driving car decision making
- **Finance** — Portfolio optimization, algorithmic trading
- **Healthcare** — Treatment optimization, drug discovery
- **Energy** — Data center cooling (DeepMind), power grid optimization
- **LLM Alignment** — RLHF for aligning language models with human preferences

## References

- Mnih, V. et al. (2015). Human-level control through deep reinforcement learning. *Nature*, 518(7540).
- Schulman, J. et al. (2017). Proximal Policy Optimization Algorithms. *arXiv*.
- Hafner, D. et al. (2023). Mastering Diverse Domains through World Models. *arXiv*.
- Brohan, A. et al. (2023). RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control. *CoRL*.
- Black, K. et al. (2024). OpenVLA: An Open-Source Vision-Language-Action Model. *arXiv*.
- LeCun, Y. (2022). A Path Towards Autonomous Machine Intelligence. *OpenReview*.

## Author

**Dr. Farshid Pirahansiah** — [LinkedIn](https://linkedin.com/in/pirahansiah) | [GitHub](https://github.com/pirahansiah)
