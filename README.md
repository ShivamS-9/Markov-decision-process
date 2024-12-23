# Markov Decision Process (MDP) - Assignment 3.2

This repository contains the solution for the "Markov Decision Process" assignment from the Machine, Data and Learning course.

## Assignment Overview

The task involves implementing the **Value Iteration** algorithm to solve an MDP in a grid world environment. The goal is for an agent to navigate a grid with rewards, penalties, and step costs, optimizing its policy to reach the goal state while avoiding obstacles.

### Key Tasks:
1. **Implement Value Iteration** to calculate the optimal policy and utility values for each state.
2. **Run experiments** with different values of the probability parameter `p` (ranging from 0.1 to 0.9) to observe how it affects the agent's decision-making process.
3. **Manual calculation** of utility values for two iterations to verify the correctness of the algorithm.

### Dependencies:
- Python 3.x
- numpy
- matplotlib
- prettytable

The algorithm will print the utility values and the final policy for each `p` value.
