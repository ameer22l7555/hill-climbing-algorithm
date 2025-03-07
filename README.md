# Hill Climbing Algorithm Implementation

This repository contains a Python implementation of the Hill Climbing optimization algorithm applied to finding the shortest path between nodes in a graph.

## Overview

The Hill Climbing algorithm is a local search optimization technique that continuously moves in the direction of increasing value to find the optimal solution. In this implementation, it is used to optimize path distances between nodes in a graph.

## Results

The algorithm demonstrates significant improvement in path optimization:

### Initial Path
- Route: E → F → A → D → B → C → G → E
- Total Distance: 35.70 units

### Optimized Path
- Route: A → B → E → C → F → D → G → A
- Total Distance: 21.22 units

This shows a substantial improvement in the total path distance through optimization.

## Implementation Details

The implementation is provided in a Jupyter notebook (`HillClimbing.ipynb`) that includes:
- Graph representation
- Path distance calculations
- Hill climbing optimization logic
- Visualization of paths

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python packages (numpy, matplotlib, etc.)

## Usage

1. Clone the repository
2. Open the Jupyter notebook
3. Run all cells to see the algorithm in action

## Visualization

The notebook includes visualizations of both the initial and optimized paths, helping to understand the improvement in the solution.

## License

This project is open source and available under the MIT License.