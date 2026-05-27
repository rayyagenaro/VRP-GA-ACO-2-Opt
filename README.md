# Vehicle Routing Problem Optimization using GA, ACO, and 2-Opt

This project implements several optimization techniques to solve the Vehicle Routing Problem (VRP), including Genetic Algorithm (GA), Ant Colony Optimization (ACO), and 2-Opt local search. The objective is to find the most efficient route for vehicle delivery while minimizing total travel distance and improving operational efficiency.

## Features
- Vehicle Routing Problem (VRP) solver
- Genetic Algorithm (GA) optimization
- Ant Colony Optimization (ACO)
- 2-Opt local search improvement
- Route distance minimization
- Route visualization and comparison
- Performance evaluation between algorithms

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib

## Optimization Methods

### Genetic Algorithm (GA)
An evolutionary algorithm that uses:
- Selection
- Crossover
- Mutation

to generate optimal routing solutions iteratively.

### Ant Colony Optimization (ACO)
A swarm intelligence-based algorithm inspired by ant colony behavior and pheromone trails to discover efficient routes.

### 2-Opt
A local search optimization technique used to improve an existing route by swapping route segments to reduce total distance.

## Objectives
- Minimize total delivery distance
- Improve routing efficiency
- Compare optimization algorithm performance
- Generate optimized delivery routes

## Output
- Optimized vehicle routes
- Distance calculation results
- Route visualization graphs
- Algorithm performance comparison

## Project Structure
```bash
├── data/
├── src/
├── results/
├── main.py
├── requirements.txt
└── README.md
