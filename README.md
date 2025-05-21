# Robust Optimization under Total Uncertainty – MOGPL Project

## Overview

This project was carried out as part of the MOGPL course (Modélisation, optimisation, graphes, programmation linéaire). We explored robust optimization techniques for decision-making under total uncertainty.

## Example Problem

We worked on a robust knapsack problem involving the selection of projects with fixed costs and uncertain utilities.

## Robustness Criteria Implemented

We studied and implemented four robust criteria for maximization problems:

- **Maximin**: Maximize the minimum utility across scenarios.
- **Minimax Regret**: Minimize the maximum regret compared to optimal solutions in each scenario.
- **Max OWA (Ordered Weighted Average)**: Maximize a weighted sum favoring low-performing scenarios.
- **Min OWA of Regrets**: Minimize a weighted sum of ordered regrets, focusing on the largest regrets.

## Technical Approach

Each criterion was reformulated into a linear or mixed-integer linear program to be solved with standard optimization solvers (GUROBI). 

## Files

- `Ex1.ipynb`: Linearization of **maximin** and **minimax regret** criteria  
- `Ex2.ipynb`: Linearization of the **max OWA** criterion  
- `Ex3.ipynb`: Application to robust **pathfinding in graphs** and analysis of **computational complexity**

## Authors

- [Karim Ellouze]
- [Philipp Hanussek](https://www.linkedin.com/in/philipp-hanussek-689bb7249/)
