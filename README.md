Absolutely, here's the updated README file with brief explanations of each of the algorithms implemented in your Pygame application:

# Pygame Pathfinding Visualization

This is a Pygame application for visualizing path-finding algorithms. The user can draw on the grid using the mouse and then select one of the following keys to start the algorithm: 'D' for Dijkstra's algorithm, 'A' for A* algorithm, or 'B' for BFS algorithm.

## Installation

To use this application, you will need to have Pygame installed. You can install Pygame using pip with the following command:

```
pip install pygame
```

## Usage

To run the application, run the `pathFindingVis.py` file. Once the application is running, use the mouse to draw on the grid. Then, press one of the following keys to start the algorithm:

- 'D' for Dijkstra's algorithm
- 'A' for A* algorithm
- 'B' for BFS algorithm

When you are finished, press the 'C' key to clear the screen and start over.

## Algorithms

Here's a brief explanation of each of the algorithms implemented in the Pygame application:

### Dijkstra's Algorithm

Dijkstra's algorithm is a weighted shortest-path algorithm that can be used to find the shortest path between a starting node and all other nodes in a graph. It works by keeping track of the distance from the starting node to each other node in the graph, and continuously selecting the node with the smallest distance and updating the distances of its neighbors until all nodes have been visited. This algorithm guarantees to find the shortest path from the starting node to all other nodes in the graph.

### A* Algorithm

A* algorithm is a heuristic-based algorithm that can be used to find the shortest path between a starting node and a target node in a graph. It works by maintaining a priority queue of nodes to visit, with the priority being the estimated distance from the starting node to the target node. This estimated distance is calculated using a heuristic function that estimates the distance between a node and the target node. A* algorithm guarantees to find the shortest path from the starting node to the target node, as long as the heuristic function is admissible and consistent.

### Breadth-First Search (BFS) Algorithm

Breadth-First Search (BFS) algorithm is an algorithm that can be used to traverse a graph in breadth-first order. It starts at a specified node and visits all the nodes at the same level before moving to the next level. BFS algorithm can be used to find the shortest path between two nodes in an unweighted graph. It guarantees to find the shortest path between the starting node and the target node if the graph is unweighted.
