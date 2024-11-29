# Reinforcement Learning: CliffWalking and Blackjack

## Description
This repository explores **Reinforcement Learning (RL)** concepts through two classic environments: **CliffWalking** and **Blackjack**. RL is a machine learning paradigm where agents learn to make decisions by interacting with an environment to maximize cumulative rewards.

---

## Environments

### **1. CliffWalking**
- **Objective**: Navigate a grid-based environment from a starting point to a goal while avoiding the "cliff" (a set of dangerous states that result in heavy penalties).
- **Features**:
  - Rewards: Negative for each step, and a large penalty for falling off the cliff.
  - States: Represent positions on a grid.
  - Actions: Move up, down, left, or right.
- **Challenges**:
  - The agent must balance exploration and exploitation to find the shortest path without falling off the cliff.
  - Reinforcement learning algorithms (e.g., **Q-Learning**) are used to compute the optimal policy.

### **2. Blackjack**
- **Objective**: Develop an optimal strategy for playing the game of Blackjack.
- **Features**:
  - Rewards: Positive for winning, negative for losing.
  - States: Represent the sum of the player’s cards, the dealer’s visible card, and whether the player has a usable ace.
  - Actions: "Hit" (take another card) or "Stick" (end the turn).
- **Challenges**:
  - High variability in outcomes due to stochastic card drawing.
  - The agent learns to maximize rewards by balancing the risk of exceeding 21 with the chance of beating the dealer.

---

## Implemented Algorithms

1. **Q-Learning**:
   - A model-free algorithm where the agent learns a **Q-value function** to estimate the expected utility of actions in a given state.
   - Updates Q-values using the formula:
     ```math
     Q(s, a) ← Q(s, a) + α [r + γ max_a' Q(s', a') - Q(s, a)]
     ```
   - Works well for both deterministic (CliffWalking) and stochastic (Blackjack) environments.
---

## Learning Objectives
- Understand the fundamental concepts of **Reinforcement Learning**, such as rewards, states, actions, and policies.
- Compare and analyze the performance of **Q-Learning**  in deterministic and stochastic environments.
- Explore how exploration-exploitation strategies (e.g., epsilon-greedy) affect learning outcomes.

---
