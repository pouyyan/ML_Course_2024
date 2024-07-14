# Deep Q-Learning Agents for LunarLander-v2
This repository contains Python code implementing two variants of Deep Q-Learning (DQN) agents and Double Deep Q-Learning (DDQN) agents for solving the LunarLander-v2 environment from OpenAI's Gym.

## Requirements
To run the code, ensure you have the following installed:

Python 3.x

Jupyter Notebook (for running interactively)

## Setup

Ensure dependencies are installed as per requirements.txt.

Run Jupyter Notebook or any Python environment that supports interactive sessions.

Usage
## DQN Agent
DQNAgent: Implements a basic DQN agent with experience replay.

Training involves initializing the environment, training the agent, and saving models periodically.
## DDQN Agent
DDQNAgent: Extends DQNAgent with Double Deep Q-Learning capabilities.

Training involves initializing the environment, training the agent, updating target networks, and saving models periodically.
## Visualization
Training progress and rewards can be visualized using matplotlib to track agent performance over episodes.
## Code Organization
dqn_agent.py: Defines the DQNAgent class for DQN training.

ddqn_agent.py: Defines the DDQNAgent class for DDQN training.

utils.py: Contains utility functions such as experience replay (ExperienceReplay).

main.ipynb: Jupyter Notebook demonstrating agent training and visualization.
## Running Examples
Example usage can be found in main.ipynb, where DQN and DDQN agents are trained on the LunarLander-v2 environment.

## References
OpenAI Gym

Stable Baselines3

License

This project is licensed under the MIT License - see the LICENSE file for details.
