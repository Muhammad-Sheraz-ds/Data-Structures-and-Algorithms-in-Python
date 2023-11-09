# Circular Linked List Implementation

This Python implementation provides a basic Circular Linked List structure with various functionalities.

## Circular Linked List

A Circular Linked List is a linear data structure in which the last node of the list points back to the first node, creating a circle. It can be traversed starting from any node, and operations like insertion and deletion can be performed efficiently.

## Class Structure

### Node
- **Attributes:**
  - `value`: The value of the node.
  - `next_node`: Reference to the next node in the circular linked list.

### CircularLinkedList
- **Attributes:**
  - `head`: Reference to the head (first node) of the circular linked list.
  - `tail`: Reference to the tail (last node) of the circular linked list.
  - `size`: The number of nodes in the circular linked list.

### LinkedListIterator
- **Attributes:**
  - `current`: Reference to the current node being iterated.
  - `index`: Index of the current iteration.
  - `length`: Length of the circular linked list.

### Functions and Time Complexity (Worst and Best Cases) and Space Complexity

| Function                            | Description                                   | Worst Case Time Complexity | Best Case Time Complexity | Space Complexity (Auxiliary) |
|-------------------------------------|-----------------------------------------------|----------------------------|---------------------------|-------------------------------|
| `insert_at_end(value)`              | Inserts a node with the given value at the end of the circular linked list. | O(1)                   | O(1)                      | O(1)                          |
| `insert_at_beginning(value)`        | Inserts a node with the given value at the beginning of the circular linked list. | O(1)                   | O(1)                      | O(1)                          |
| `insert_at_index(value, index)`     | Inserts a node with the given value at the specified index in the circular linked list. | O(n)             | O(1)                      | O(1)                          |
| `update_node(value, index)`         | Updates the value of the node at the specified index. | O(n)                     | O(1)                      | O(1)                          |
| `remove_last_node()`                | Removes the last node from the circular linked list. | O(n)                      | O(1)                      | O(1)                          |
| `remove_first_node()`               | Removes the first node from the circular linked list. | O(1)                     | O(1)                      | O(1)                          |
| `remove_at_index(index)`            | Removes the node at the specified index from the circular linked list. | O(n)                | O(1)                      | O(1)                          |
| `remove_node(value)`                | Removes the node with the specified value from the circular linked list. | O(n)                | O(1)                      | O(1)                          |
| `size_of_linked_list()`             | Returns the size (number of nodes) of the circular linked list. | O(1)               | O(1)                      | O(1)                          |
| `display()`                         | Displays the values of the circular linked list. | O(n)                      | O(n)                      | O(1)                          |

**Note:**
- Time complexity is given in terms of the number of nodes (n).
- Space complexity is specified for auxiliary space, not including the space required by the input and output.

Feel free to use this Circular Linked List implementation for your projects and modify it as needed!
