# Singly Linked List Implementation

This Python implementation provides a basic Singly Linked List structure with various functionalities.

## Singly Linked List

A Singly Linked List is a linear data structure where elements are stored in nodes, and each node points to the next node in the sequence.

## Class Structure

### Node
- **Attributes:**
  - `value`: The value of the node.
  - `next_node`: Reference to the next node.

### MyLinkedList
- **Attributes:**
  - `head`: Reference to the head (first node) of the linked list.

### Functions and Time Complexity (Worst and Best Cases) and Space Complexity

| Function                          | Description                                   | Worst Case Time Complexity | Best Case Time Complexity | Space Complexity (Auxiliary) |
|-----------------------------------|-----------------------------------------------|----------------------------|---------------------------|-------------------------------|
| `append(value)`                   | Appends a node with the given value to the end of the linked list. | O(n)                   | O(1)                      | O(1)                          |
| `insert_at_beginning(value)`      | Inserts a node with the given value at the beginning of the linked list. | O(1)              | O(1)                      | O(1)                          |
| `insert_at_index(value, index)`   | Inserts a node with the given value at the specified index. | O(n)                   | O(1)                      | O(1)                          |
| `insert_at_end(value)`            | Inserts a node with the given value at the end of the linked list. | O(n)                   | O(1)                      | O(1)                          |
| `update_node(value, index)`       | Updates the value of the node at the specified index. | O(n)                   | O(1)                      | O(1)                          |
| `remove_first_node()`             | Removes the first node from the linked list.  | O(1)                       | O(1)                      | O(1)                          |
| `remove_last_node()`              | Removes the last node from the linked list.  | O(n)                        | O(1)                      | O(1)                          |
| `remove_at_index(index)`          | Removes the node at the specified index.  | O(n)                        | O(1)                      | O(1)                          |
| `remove_node(value)`              | Removes the first occurrence of the node with the specified value. | O(n)                | O(1)                      | O(1)                          |
| `size_of_linked_list()`           | Returns the number of nodes in the linked list. | O(n)                      | O(n)                      | O(1)                          |
| `display()`                       | Displays the values of the linked list. | O(n)                       | O(n)                      | O(1)                          |

**Note:**
- Time complexity is given in terms of the number of nodes (n).
- Space complexity is specified for auxiliary space, not including the space required by the input and output.

Feel free to use this Singly Linked List implementation for your projects and modify it as needed!
