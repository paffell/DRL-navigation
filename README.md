[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# DRL for banana collecting

### Introduction

This project solves the problem of collecting bananas using DRL.

### Problem

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.



    
##### Note
The project environment is similar to, but not identical to the Banana Collector environment on the Unity ML-Agents GitHub page.


### The Environment
Follow the instructions below to explore the environment on your own machine! You will also learn how to use the Python API to control your agent.

Step 1: Clone the DRLND Repository
If you haven't already, please follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up your Python environment. These instructions can be found in `README.md` at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.


Step 2: Download the Unity Environment

The environment is included (Windows 64-bit version), other versions can be downloaded from:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)


### Algorithms

##### DQN

##### Double DQN

##### Prioritized replay (TBD)


### Structure

This repository consists of

`Navigation.ipynb` - notebook for running the experiments

`model.py` - DL model definition

`dqn_agent.py`, `double_dqn_agent.py`, `dqn_prioritized_replay_agent.py` - Agent class

`checkpoint_best.pth` - already trained agent

`Banana_Windows_x86_64` - problem environment

### How to run

Follow the instructions in `Navigation.ipynb`.

The notebook includes both `Training` and `Simulation` parts.


