# Artificial Intelligence Algorithms

This repository contains implementations of core **Artificial Intelligence and Machine Learning algorithms written from scratch in Python**.  
The projects focus on search algorithms, evolutionary computation, and unsupervised learning, demonstrating how classic AI problems can be solved without relying on external ML libraries.

## Topics Covered

- Heuristic search algorithms  
- Clustering algorithms  
- Distance computation and optimization problems  
- Data visualization and algorithm analysis  

All algorithms were implemented manually to demonstrate a strong understanding of the underlying concepts.

---

# Projects

## 1. Travelling Salesman Problem – Search Algorithms

Implemented search-based approaches to solve the **Travelling Salesman Problem (TSP)** using geographic city coordinates.

### Overview
The Travelling Salesman Problem is a classic optimization problem where the goal is to determine the shortest route that visits each city exactly once and returns to the starting point.

### Implementation
- Built a **distance matrix generator** using Euclidean distance calculated from city latitude and longitude coordinates.
- Implemented search algorithms to explore possible routes and determine optimal or near-optimal paths.

### Algorithms Implemented
- **Depth-First Search (DFS)**
- **Breadth-First Search (BFS)**

### Key Features
- Custom distance matrix computation
- Graph traversal for route exploration
- Route distance evaluation and comparison
- Performance comparison between DFS and BFS strategies

### Technologies
- Python
- CSV data processing
- Algorithm design and search strategies

---

## 2. N Queens Optimization

Developed a **Genetic Algorithm** to solve the classical **N-Queens optimization problem**.

### Problem Description
The objective is to place **N chess queens on an N×N board** such that no two queens threaten each other.

Constraints:
- No queens share the same row
- No queens share the same column
- No queens share the same diagonal

### Implementation
A population-based evolutionary algorithm was designed to iteratively improve candidate solutions.

### Genetic Algorithm Components
- Chromosome representation of board configurations
- Fitness function evaluating number of queen conflicts
- Parent selection
- Crossover and mutation operations
- Iterative population evolution toward optimal solutions

### Key Concepts Demonstrated
- Evolutionary search techniques
- Fitness evaluation
- Optimization using stochastic processes

### Technologies
- Python
- Evolutionary algorithm design

---

## 3. K-Means Clustering Implementation 

Implemented the **K-Means clustering algorithm from scratch** to group observations into clusters based on feature similarity.

### Dataset
- 30 observations
- 2 numerical features

### Implementation Details
The clustering algorithm was implemented without using machine learning libraries.

### Algorithm Steps
1. Select the first **k data points as initial centroids**
2. Assign each observation to the nearest centroid using **Euclidean distance**
3. Label each data point according to its assigned cluster
4. Recalculate centroids by averaging all points within each cluster
5. Repeat the process until centroids no longer change

### Outputs
- Final cluster assignments
- Cluster sizes
- Final centroid coordinates
- Visualization of clustered data

### Visualization
Scatter plots were generated to display:
- Original observations
- Final cluster groupings
- Cluster centroids

### Technologies
- Python
- Data visualization
- Unsupervised learning algorithms

---
