# Practice 1: Planning with Blind/Heuristic Search

## Description
This project implements various search algorithms to solve planning problems in artificial intelligence. The algorithms aim to find the best possible solution to a problem defined as a state-space search, using both blind and heuristic strategies.

---

## Implemented Algorithms
1. **Blind Search**:
   - **Breadth-First Search (BFS)**: Explores all nodes at the same level before moving to the next level.
   - **Depth-First Search (DFS)**: Explores as deep as possible in each branch before backtracking.

2. **Heuristic Search**:
   - **A\***: This algorithm uses both the current cost (`g(n)`) and an estimated cost to the goal (`h(n)`) to prioritize node expansion. 
     - **Function**: `f(n) = g(n) + h(n)`
     - **Key Features**:
       - It ensures optimality if the heuristic `h(n)` is admissible (i.e., it never overestimates the actual cost to the goal).
       - Combines the strengths of **BFS** and heuristic-driven search by balancing exploration and cost minimization.
       - Commonly used in problems like the **8-puzzle**, pathfinding etc..

---

## Learning Objectives
- Understand and apply blind and heuristic search algorithms.
- Evaluate the performance of different search strategies in terms of time and solution quality.
- Design effective heuristic functions for planning problems.
- Explore the trade-offs between optimality, completeness, and computational efficiency in search algorithms.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone url of this repository
