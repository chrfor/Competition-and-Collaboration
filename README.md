# Competition-and-Collaboration
Udacity Deep Reinforcement Learning 

See detailed instruction : github deep reinforcement learning competition and collaboration

This folder contains the different files which are necessary to make 2 agents solving Unity Tennis environment with an average score over 100 episodes > 100.
See here under the pre requisites from Udacity to install and Test Unity Environmnent.

The files in this folders have to be installed in a single repository.
.In the Jupyter Notebook <Tennisa> you find 
>the call to the libraries
>how to start Unity Tennis environment
>how to call the API to interact with Unity Tennis environment
>The code to train the DDPG Agent
.ddpg-agent.py : The DDPG agent which have been adapted from the Udacity DDPG Pendulum agent
.model.py :  The document which encode the Actor and Critic Neural Network which have been adapted from DDPG Pendulum
.The checkpoints actor and critic files where you find the Neural Network Weights
.Unity environment log

NB : Python libraries folder have not been uploaded but need to be installed in the same folder


Detailed instruction from  github deep reinforcement learning competition and collaboration
https://github.com/udacity/deep-reinforcement-learning/blob/master/p3_collab-compet/README.md

Trained Agent
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
This yields a single score for each episode.
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

Getting Started

Download the environment from one of the links below. You need only select the environment that matches your operating system:

Linux: click here
Mac OSX: click here
Windows (32-bit): click here
Windows (64-bit): click here
(For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)

Place the file in the DRLND GitHub repository, in the p3_collab-compet/ folder, and unzip (or decompress) the file.

Instructions

Follow the instructions in Tennis.ipynb to get started with training your own agent!

