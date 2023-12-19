# Graph Traversal Class

The `Graph` class provides functionality to manage and traverse graphs. It utilizes a Node-based structure to represent vertices and their connections in a graph.

## Class Methods

### `add_vertex(st)`
Add a vertex to the graph.

### `add_directed_edge(from_loc, to_loc)`
Add a directed edge between two vertices.

### `add_undirected_edge(from_loc, to_loc)`
Add an undirected edge between two vertices.

### `traverse_reachable_graph(start)`
Traverse the graph starting from a specified vertex.

### `traverse_complete_graph()`
Traverse the entire graph.

### `explore_network(vertex_no, seen)`
Explore the graph from a specific vertex, marking visited vertices.

### `get_vertex(vno)`
Retrieve the label of a specific vertex.

### `find_vertex(st)`
Find the index of a vertex in the graph by its label.

## Time and Space Complexity

### Time Complexity
- **Add Vertex**: O(1) - Constant time complexity.
- **Add Directed/Undirected Edge**: O(1) - Constant time complexity.
- **Traverse Reachable Graph (DFS)**: O(V + E) - Time complexity is based on the number of vertices (V) and edges (E) in the graph.
- **Traverse Complete Graph (DFS)**: O(V + E) - Time complexity is based on the number of vertices (V) and edges (E) in the graph.

### Space Complexity
- **Add Vertex**: O(1) - Constant space complexity.
- **Add Directed/Undirected Edge**: O(1) - Constant space complexity.
- **Traverse Reachable Graph (DFS)**: O(V) - Space complexity is based on the number of vertices (V).
- **Traverse Complete Graph (DFS)**: O(V) - Space complexity is based on the number of vertices (V).

The time and space complexities are affected by the number of vertices and edges in the graph, especially during traversals where all vertices and edges may be explored.

