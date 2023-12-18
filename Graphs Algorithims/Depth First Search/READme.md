# Depth-First Search (DFS) Algorithm 

## Introduction

Depth-First Search (DFS) is a graph traversal algorithm that explores as far as possible along each branch before backtracking. This README provides an overview of the DFS algorithm implemented in the `Graph` class and its various aspects.

## Functions

### `Graph` Class

#### `dfs(source_vertex, visualize=False)`

Performs depth-first search traversal starting from the specified source vertex. It updates vertex colors, distances, and predecessors during the traversal. Optionally, the traversal can be visualized if the `visualize` parameter is set to `True`.

#### `visualize_graph()`

Generates a visualization of the graph using NetworkX and Matplotlib, with vertices colored based on their DFS traversal status.

#### `draw_graph()`

Generates a basic visualization of the graph using NetworkX and Matplotlib.

#### `add_vertex(label=None)`

Adds a vertex to the graph with an optional label.

#### `add_edge(vertex1, vertex2)`

Connects two vertices with an edge, establishing a relationship between them.

## Time and Space Complexity

- **Time Complexity:** O(V + E), where V is the number of vertices and E is the number of edges. DFS visits each vertex and edge once.
  
- **Space Complexity:** O(V), where V is the number of vertices. The space is used to store information about each vertex during the traversal.

## Advantages

- **Simplicity:** DFS is a straightforward algorithm to implement.
  
- **Memory Efficiency:** It requires less memory compared to breadth-first search (BFS) as it explores as far as possible before backtracking.

## Disadvantages

- **Non-Optimal Path:** DFS doesn't guarantee finding the shortest path between two vertices.

## Uses and Applications

- **Graph Traversal:** DFS is commonly used for graph traversal and searching.

- **Topological Sorting:** DFS can be used to perform topological sorting of directed acyclic graphs.

- **Connected Components:** DFS helps identify connected components in an undirected graph.

- **Maze Solving:** DFS can be employed to solve mazes and navigate through pathways.
- 