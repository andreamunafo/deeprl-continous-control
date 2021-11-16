# Continuous Control of a Double-Jointed Arm using Reinforcement Learning
This project solves the Unity ML-Agents continuous control environment through reinforcement learning.

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

There are 20 identical agents, each with its own copy of the environment.
The environment is considered solved when the agents get an average score of +30 (over 100 consecutive episodes, and over all agents)


<p align="center">
<img src="pics/continuous-control.gif" width="400" height=250>
<!--img src="pics/untrained.gif" width="300" height=250-->
</p>


# Getting Started

## Installing dependencies

The recommended way of using this repository is through Anaconda.

Set up your world environment:
```
conda create --name continuous-control python=3.6
```

and activate it:

```
source activate continuous-control
```
Install dependencies:

```
cd python/
pip install .
```

Since this repository uses jupyter notebook, install the corresponding banana-navigation kernel:

```
python -m ipykernel install --user --name drlnd --display-name "continuous-control"
```
Finally, in jupyter notebook, before running the code, make sure that the appropriate kernel is selected.

## How to run it

Run the `continous-control.ipynb` notebook.
