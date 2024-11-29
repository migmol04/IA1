# Heuristic Search Study

## Description
This repository contains code and examples designed to study **heuristic search algorithms** in artificial intelligence. Heuristic search uses additional information (heuristics) to guide the search process toward the goal more efficiently than blind search.

---

## Contents
The repository includes implementations of the following heuristic search algorithms:

1. **A\***:
   - Combines the cost to reach the current node (`g(n)`) and the estimated cost to reach the goal (`h(n)`).
   - Formula: `f(n) = g(n) + h(n)`.
   - Ensures an optimal solution if the heuristic function is admissible (does not overestimate the true cost).

2. **Greedy Best-First Search**:
   - Expands the node that appears closest to the goal based only on the heuristic value (`h(n)`).
   - Does not guarantee an optimal solution but can be faster in certain cases.

---

## Objectives
- Understand the mechanics of heuristic search algorithms.
- Learn how to design and implement heuristic functions for different problems.
- Compare heuristic search with blind search in terms of efficiency and optimality.

---
