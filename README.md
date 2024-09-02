# Optimized-Scheduling-for-CS-Department

# Optimized Scheduling for CS Department

## Introduction
This project aims to design and implement an optimized schedule for the Computer Science department for the upcoming semester. The focus is on efficiently allocating lectures to timeslots while preventing conflicts, and recognizing the critical role of effective scheduling in enhancing the academic experience for both students and faculty.

## Graph Coloring Problem

### Problem Statement
Graph coloring is a well-known problem in graph theory. The objective is to assign colors to vertices of a graph such that no two adjacent vertices share the same color. This project represents courses as vertices and conflicts as edges, creating a graph to model the scheduling problem. The goal is to find a proper vertex coloring that minimizes the number of colors (timeslots) used, ensuring no conflicts between overlapping lectures.

### Approaches to Solving the Problem
- **Greedy Algorithms**: Simple but may not yield the optimal solution.
- **Backtracking**: More computationally intensive but can often find optimal solutions.
- **Graph Coloring Heuristics**: Includes genetic algorithms, simulated annealing, and tabu search to efficiently handle larger instances.

### Complexity and NP-Hardness
The Graph Coloring Problem is NP-hard, meaning there is no known polynomial-time algorithm to solve it unless \( P = NP \). For large graphs, heuristic methods are typically preferred.

### Real-world Applications
- **Scheduling**: Assigning university courses or tasks in computing systems.
- **Wireless Networks**: Frequency assignment to avoid interference.
- **Register Allocation**: Optimizing memory usage in compilers.

## Local Search Algorithm

### Overview
Local search is a heuristic method used to tackle computationally challenging optimization problems. It iteratively makes local changes to a candidate schedule until an optimal solution is found or a specified time limit is reached.

### How It Works
1. **Initialization**: Start with an initial solution, generated randomly or using a greedy method.
2. **Evaluation**: Assess the quality of the current solution using an objective function.
3. **Termination Check**: Ensure the algorithm stops based on predefined criteria (e.g., number of iterations, improvement level, or time limit).
4. **Local Neighborhood Exploration**: Identify and evaluate neighboring solutions that differ slightly from the current one.
5. **Move to a Neighbor**: Select and move to a better neighboring solution.
6. **Update Current Solution**: Adopt the chosen neighbor as the new current solution.
7. **Iteration**: Repeat the process until the termination criterion is met.

### Why Use a Local Search Algorithm?
- **Computational Efficiency**: Efficiently handles large solution spaces.
- **Handling Complexity**: Suitable for complex problems with many variables and constraints.
- **Constraint Handling**: Effectively explores feasible regions of the solution space.
- **Simplicity**: Easier to implement compared to global optimization techniques.
- **Exploration vs. Exploitation**: Balances exploring new solutions with refining existing ones.

## Implementation
Each lecture is defined by attributes such as the teacher, room, students, and time (represented as a color in the graph). These attributes are crucial for constructing the initial graph and applying the graph coloring and local search algorithms to generate an optimized, conflict-free schedule.

## Code link:
https://colab.research.google.com/drive/1d5dMsK8YdE_WhUuNgAoP926JUjRXsgVQ?usp=sharing

## Contact
For any inquiries or feedback, please contact Fay Alomar at X @coderfay.

