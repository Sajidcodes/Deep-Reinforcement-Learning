![Deep Reinforcement Learning](![image](https://github.com/Sajidcodes/Deep-Reinforcement-Learning/assets/101083684/920dbc55-e0d5-421e-9ae3-d5e5e75bba52))



# Overview
This repository contains implementations of various Deep Reinforcement Learning (DRL) methods for the Lunar Lander environment provided by OpenAI's Gym. The goal is to enable the lunar lander to safely land on the pad between two yellow flags. The project tasks include implementing policy gradient, actor-critic, and experimenting with parameter tuning for better performance.

# Environment Details
Task: Deep Reinforcement Learning
Environment: Lunar Lander in Gym of OpenAI
State: 8-dimensional vector representing the coordinates, linear velocities, angle, angular velocity, and leg contact status.
Action: 4 discrete actions, including acceleration and lateral movements.
Reward: Rewards are given for successful landing, staying on the landing pad, and leg contact. Penalties are incurred for crashing and engine usage.
# Project Tasks
1. Policy Gradient Implementation
Sample code applies policy gradient network.
Number of epochs: 100.
Running time: Approximately 1 minute.
2. Simple Tuning
Tune parameters (learning rate, #epochs, etc.) until total reward converges.
3. Medium Difficulty
Change reward to accumulative decaying reward.
4. Hard Difficulty
Implement actor-critic.
# Evaluation
The evaluation is based on the average total reward over 5 tests. Higher average total rewards indicate better performance.

I would recommend using Colab. If you use an environment other than Colab, fix reproducibility issues yourself.
It won't use GPU by default; the training should finish within 30 minutes.
Good luck, and enjoy exploring Deep Reinforcement Learning in the lunar environment!





