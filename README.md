
# Udacity Deep Reinforcement Learning Nanodegree - Project 2 (Continuous Control)

## Description

This project aims the develpment of a training routine for a double-jointed arm, based on the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.
The goal is to maintain the position of the arm's hand in the desired location. A reward of +0.1 is given for every step that the hand is in this location.

The state space has 33 dimensions, comprising the position, rotation, velocity, and angular velocities of the arm.
The action space is a vector with 4 dimensions (continuous numbers between -1 and 1), comprising the torque applied to the 2 joints.

The environment is configured for a single agent, but another configuration could be used to train multiple agents in parallel.
The task is episodic and the solution is achieved when the agent gets an average score of +30 for 100 consecutive episodes.

## Steps

1. Install the following python libraries:
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) (v0.4.0)
- PyTorch (v0.4.0)
- NumPy
- Matplotlib

2. The OS chosen for the development was Ubuntu, for which there are two possible environment files available for download:
- [with visual feedback](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
- [without visual feedback](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux_NoVis.zip)

3. Download and uncompress the compatible environment file.

4. Run the `Continuous_Control.ipynb` notebook to train and evaluate the agent.

