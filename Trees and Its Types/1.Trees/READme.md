# Tree Implementation

This Python implementation provides a basic Tree structure with various functionalities using linked nodes.

## Tree

A Tree is a hierarchical data structure consisting of nodes connected by edges. Each node has a parent (except for the root) and zero or more children.

## Class Structure

### Node
- **Attributes:**
  - `data`: The value of the node.
  - `children`: List of child nodes.

### Tree
- **Attributes:**
  - `root`: Reference to the root node.
  
### Functions and Time Complexity (Worst and Best Cases) and Space Complexity

| Function                              | Description                                   | Worst Case Time Complexity | Best Case Time Complexity | Space Complexity (Auxiliary) |
|---------------------------------------|-----------------------------------------------|----------------------------|---------------------------|-------------------------------|
| `addnode(n, p)`                       | Adds a node as a child to an existing node.   | O(n)                       | O(1)                      | O(1)                          |
| `Display()`                           | Displays the nodes of the Tree.               | O(n)                       | O(n)                      | O(h)                          |
| `size()`                              | Returns the number of nodes in the Tree.      | O(n)                       | O(n)                      | O(h)                          |
| `pre_order_traversal()`               | Pre-order traversal of the Tree.              | O(n)                       | O(n)                      | O(h)                          |
| `post_order_traversal()`              | Post-order traversal of the Tree.             | O(n)                       | O(n)                      | O(h)                          |
| `in_order_traversal()`                | In-order traversal of the Tree.               | O(n)                       | O(n)                      | O(h)                          |
| `leaves_count()`                      | Returns the number of leaves in the Tree.     | O(n)                       | O(n)                      | O(h)                          |
| `search_node(v)`                      | Searches for a node with a given value.       | O(n)                       | O(1)                      | O(1)                          |
| `remove(v)`                           | Removes a node with a given value.            | O(n)                       | O(n)                      | O(h)                          |
| `cut(copy)`                           | Cuts a subtree rooted at a specified node.   | O(n)                       | O(n)                      | O(h)                          |
| `update(old, new)`                    | Updates the value of a node in the Tree.     | O(n)                       | O(n)                      | O(h)                          |
| `cut_paste(copy, paste)`              | Cuts a subtree and pastes it as a child to another node. | O(n)            | O(n)                      | O(h)                          |
| `traverse_by_queue()`                 | Level-order traversal of the Tree using a queue. | O(n)                  | O(n)                      | O(h)                          |

**Note:**
- Time complexity is given in terms of the number of nodes (n) or the height of the tree (h).
- Space complexity is specified for auxiliary space, not including the space required by the input and output.

Feel free to use this Tree implementation for your projects and modify it as needed!
