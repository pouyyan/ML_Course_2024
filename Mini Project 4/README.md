# Deep Q-Learning Agents for LunarLander-v2
This repository contains Python code implementing two variants of Deep Q-Learning (DQN) agents and Double Deep Q-Learning (DDQN) agents for solving the LunarLander-v2 environment from OpenAI's Gym.

## Links

||Google Drive <br />(including the <br /> LaTeX report file)|Google Colab|
|---|---|---|
| Links | [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1c0kVD682t4sIcBtKK-QdNBHHXsFnddQ6?usp=sharing) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10YpyxZRWM0dNsG6oDS-4DXFkcZPIFC9I?usp=sharing) |

## Requirements
To run the code, ensure you have the following installed:

Python 3.x

Jupyter Notebook (for running interactively)

## Setup

Run Jupyter Notebook or any Python environment that supports interactive sessions.

## Overview
### DQN Agent
DQNAgent: Implements a basic DQN agent with experience replay.

Training involves initializing the environment, training the agent, and saving models periodically.
### DDQN Agent
DDQNAgent: Extends DQNAgent with Double Deep Q-Learning capabilities.

Training involves initializing the environment, training the agent, updating target networks, and saving models periodically.
## Visualization
Training progress and rewards can be visualized using matplotlib to track agent performance over episodes.

## Code Organization

| Code Section | Description |
|---|---|
| dqn_agent | Defines the DQNAgent class for DQN training. |
| ddqn_agent | Defines the DDQNAgent class for DDQN training. |
| ExperienceReplay | Contains function of experience replay (ExperienceReplay). |

## Running Examples
Example usage can be found in Mini_Project_4.ipynb, where DQN and DDQN agents are trained on the LunarLander-v2 environment.

## References
OpenAI Gym

Stable Baselines3

## License

This project is licensed under the MIT License - see the LICENSE file for details.
