# Reinforcement Learning practical work
Compilation of work and assignments with my solutions for reinforcement learning thematic.
  
---
  
## Value iteration algorithm
[Value iteration algorithm implementation]() for MDP graph:
![](./value_iteration_algorithm/MDPgraph.PNG)

## Exercices with OpenAI Gym

### 1. [Dynamic programming](./openai_gym/dynamic_programming/Dynamic_Programming.ipynb)
Implementation of Dynamic Programming algorithms such as Policy Evaluation, Policy Improvement, Policy Iteration, and Value Iteration.

### 2. [Monte Carlo methods](./openai_gym/monte-carlo-methods/Monte_Carlo.ipynb)
Implementation of Monte Carlo methods for prediction and control in **[Black Jack environment](https://github.com/openai/gym/blob/master/gym/envs/toy_text/blackjack.py)**
![](./openai_gym/monte-carlo-methods/images/optimal.png)

## Bandits strategies
*Work done during the course of Thomas Bonald and Pierre Gaillard at Telecom Paris.*

Implementation and test of the performance of some usual bandit algorithms.

* **𝜀 -greedy**
* **adaptive greedy**
* **UCB**
* **Thompson sampling**

### 1. [Bandits algorithms](./bandits_strategies/stochastic-bandits/bandits_algorithms.ipynb)
Implementation of the above algorithms in a bandit environment (Bernouilli and Gaussian rewards).

### 2. [Stochastic bandits](./bandits_strategies/stochastic-bandits/lab-stochastic-bandits.ipynb)
Look at the regret and precision of these algorithms, with some statistics.

### 3. [Adversarial bandits](./bandits_strategies/adversarial-bandits/Adversarial_bandits.ipynb)
Implementation of EXP3 algorithm for simple player vs adversary game.
![](./bandits_strategies/adversarial-bandits/rock_paper_scissors.PNG)

## [Monte Carlo Tree Search](./monte_carlo_tree_search/MCTS%20--%20Connect%204-Lab2-newLab.ipynb)
*Performing monte carlo tree search for the game connect 4, by Claire Vernade.*  
  
![](./monte_carlo_tree_search/Connect4.PNG)
