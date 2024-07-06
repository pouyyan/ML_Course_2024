# LunarLander-v2 Deep Q-Network Implementation 
 
This repository contains an implementation of a Deep Q-Network (DQN) agent to solve the LunarLander-v2 environment from OpenAI Gym. The code is written in Python and utilizes PyTorch for the neural network implementation. 
 
## Requirements 
 
To run the code, you need to have the following libraries installed: 
Explain 
Use code with caution 
pip install gym==0.25.2 stable-baselines3 box2d-py pyvirtualdisplay rarfile torch 
 
  
## Usage 
 
1. Training: 
   - Run the provided Python script to train the DQN agent. 
   - The training process will save checkpoints every 50 episodes. 
   - Training logs will be printed to the console, including average reward and epsilon values. 
 
2. Evaluation: 
   - Load a trained checkpoint using the agent.load() method. 
   - Evaluate the agent's performance in the LunarLander-v2 environment. 
   - Optionally, record videos of the agent's gameplay. 
 
## Hyperparameters 
 
- Batch Size: 32 and 64 (experiments with two different batch sizes) 
- Gamma (Discount Factor): 0.99 
- Epsilon (Exploration Rate): Starts at 1.0 and decays to 0.01 
- Learning Rate: 1e-4 
- Experience Replay Buffer Size: 25000 
 
## Results 
 
- The training progress is visualized in plots showing the cumulative reward per episode. 
- Videos of the agent's gameplay are saved for selected episodes. 
 
## Future Work 
 
- Implement Double DQN or Dueling DQN for improved performance. 
- Experiment with different hyperparameter settings. 
- Evaluate the agent's generalization capabilities on other LunarLander environments. 
