## Kruskal’s Minimum Spanning Tree (MST) Algorithm

### Introduction

Kruskal’s Algorithm is a well-known greedy algorithm designed to find the minimum spanning tree (MST) of a connected, undirected graph. Similar to Prim's Algorithm, the objective of Kruskal's Algorithm is to connect all vertices of the graph with the minimum possible total edge weight. This algorithm is particularly useful in scenarios such as network design, where the goal is to establish a cost-effective and optimal network of roads, pipelines, or communication channels.

## Kruskal’s Algorithm Pseudocode

1. **Initialize an empty set MST** to store the minimum spanning tree.

2. **Sort all the edges in non-decreasing order** of their weights.

3. **Initialize a disjoint set (or union-find) data structure** to keep track of connected components.

4. **For each edge in the sorted list:**
   - If including the edge does not create a cycle in MST (i.e., the edge connects two disjoint sets):
     - Add the edge to MST.
     - Merge the two sets connected by the edge.

5. **Return MST.**

### Purpose

The primary purpose of Kruskal’s Algorithm is to identify a subset of edges forming a tree that spans all vertices in the graph, while minimizing the total weight of the edges. This optimization is crucial in various network-related problems, ensuring the establishment of an efficient and cost-effective connected infrastructure.

### Time Complexity

The time complexity of Kruskal’s Algorithm is O(E log V), where E is the number of edges and V is the number of vertices in the graph. The dominating factor is the sorting of edges by weight.

### Space Complexity

The space complexity of Kruskal’s Algorithm is O(E + V), where E is the number of edges and V is the number of vertices in the graph. This accounts for the space used to store the minimum spanning tree (MST), the edges, and the disjoint set data structure.

### Applications

Kruskal’s Algorithm finds applications in various domains:

- **Network Design**: Efficiently designing networks for communication, transportation, or resource distribution.
  
- **Clustering**: Identifying clusters or groups in data for analysis.

- **Maze Generation**: Creating mazes with optimal paths.

- **Circuit Design**: Optimizing the layout of electronic circuits.
