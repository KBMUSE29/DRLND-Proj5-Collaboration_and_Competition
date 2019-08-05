# DRLND-Proj5-Collaboration_and_Competition
This project aims to train a Unity ML agent to play Tennis using DDPG and adversarial collaboration

# Project Details
In this environment, the observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping. The goal of each agent is to keep the ball in play. Two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1.  If an agent lets the ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.  The task is episodic, and in order to solve the environment, the agent must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

# Dependencies (for RTX 2080 Super GPU)
- https://github.com/udacity/deep-reinforcement-learning#dependencies
- PyTorch v1.1.0
- Python 3.7
- CUDA 10.0
- cuDNN 7.6.2 for CUDA 10.0
- Unity ML Agents

# Instructions
1. Clone https://github.com/udacity/deep-reinforcement-learning 
2. Follow the instructions in the DRLND GitHub repository and setup the specified dependencies 
3. Clone this repository
4. Copy all files located in this cloned repository into the following cloned deep-reinforcement-learning local directory 
   "...\deep-reinforcement-learning\p3_collab-compet"
5. Unzip "Tennis_Windows_x86_64.zip" 
6. Update the file_name= directory on line 2 of section "2. Instantiate the Environment" to point to the local directory of the unzipped "Tennis_Windows_x86_64" directory 
7. Execute the code located in Tennis.ipynb after the "4. It's Your Turn!" heading

