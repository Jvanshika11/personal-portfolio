---
title: 'RL Agents for Text Flappy Bird'
date: 2023-04-15
tags: [
    "Reinforcement Learning",
    "OpenAI Gym",
    "Machine Learning",
    "Game Development"
]
image: 'cover.png'
github: 'https://github.com/Jvanshika11/Reinforcement-Learning-based-Agents-for-Text-Flappy-Bird'
draft: false
---

Developed and implemented multiple reinforcement learning agents (Q-learning and SARSA) for the Text Flappy Bird environment, conducting comprehensive performance analysis and parameter optimization. The project achieved superior game performance compared to random baseline agents, with Q-learning demonstrating optimal results through systematic hyperparameter tuning and comparative analysis of learning algorithms.

<!--more-->

## Overview
The project explores the application of reinforcement learning techniques to master the Text Flappy Bird game, a simplified version of the popular Flappy Bird. Through implementation of Q-learning and SARSA agents, the study investigates the effectiveness of different RL approaches and their parameter sensitivity. Comprehensive analysis included parameter sweeps, state-value function visualization, and performance comparisons, demonstrating the superiority of Q-learning in this environment with specific hyperparameter configurations.

## Technologies
- **Programming**: Python, Jupyter Notebooks
- **Data Processing**: NumPy, Pandas, SciPy 
- **Visualization**: Matplotlib, Seaborn
- **Environment**: OpenAI Gym
- **Algorithm Implementation**: Q-Learning, SARSA
- **Performance Analysis**: State-Value Function Visualizers, Learning curve analysis tools, Custom metrics tracking

## Implementation Details

### 1. Agent Development
- Implemented Q-learning algorithm with Bellman equation optimization
- Developed SARSA agent with on-policy learning approach
- Created random agent baseline for performance comparison
- Designed state-space representation for the game environment

### 2. Parameter Optimization
- Conducted systematic parameter sweep for step-size, epsilon, and discount factors
- Optimized hyperparameters through 10,000 episode evaluations
- Identified optimal configurations and determined distinct optimal discount factors for Q-learning and SARSA

### 3. Performance Evaluation
- Implemented comprehensive metrics tracking system
- Developed visualization tools for state-value function analysis
- Established baseline measurements using random agent
- Implemented reward and score tracking mechanisms
- Created visualization pipeline for performance metrics

### Analysis Features
- State-value function visualization
- Hyperparameter sensitivity analysis
- Performance comparison across agents
- Learning curve progression tracking
- Parameter sweep visualization
- Reward accumulation analysis
- Episode score distribution
- Convergence rate comparison

## Key Results
- Q-learning agent achieved optimal performance with specific parameter configuration
- Identified optimal hyperparameters through systematic parameter sweep
- Demonstrated superior performance of both RL agents over random baseline
- Discovered distinct optimal discount factors for different algorithms
- Achieved stable learning convergence in Q-learning implementation
- Documented SARSA's improved handling of delayed rewards
- Identified step-size and epsilon values that maximize performance
- Quantified performance differences between Q-learning and SARSA
- Mapped learning progression through episode scores

## Skills Gained
- Python programming for ML applications
- Reinforcement learning algorithm implementation and optimization
- Hyperparameter tuning and sensitivity analysis
- Game environment interaction and state space design
- Game Performance metrics development and analysis
- Scientific visualization and data presentation
- Statistical analysis and result interpretation

## Impact
The project demonstrates practical implementation of reinforcement learning algorithms in game environments, providing insights into algorithm selection and parameter optimization. The methodology and analysis framework developed can be extended to more complex environments and different reinforcement learning applications. The findings contribute to understanding the relative strengths of different RL approaches in discrete action spaces.
