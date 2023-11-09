# Doubly Linked List Implementation

This Python implementation provides a basic Doubly Linked List structure with various functionalities.

## Doubly Linked List

A Doubly Linked List is a linear data structure in which each node contains a data element and two pointers, the first pointing to the previous node, and the second pointing to the next node in the sequence.

## Class Structure

### Node
- **Attributes:**
  - `data`: The value of the node.
  - `next`: Reference to the next node.
  - `prev`: Reference to the previous node.

### doublyLinkedList
- **Attributes:**
  - `head`: Reference to the head (first node) of the doubly linked list.
  - `tail`: Reference to the tail (last node) of the doubly linked list.

### Functions and Time Complexity (Worst and Best Cases) and Space Complexity

| Function                              | Description                                   | Worst Case Time Complexity | Best Case Time Complexity | Space Complexity (Auxiliary) |
|---------------------------------------|-----------------------------------------------|----------------------------|---------------------------|-------------------------------|
| `add_node(o)`                         | Adds a node with the given value to the end of the doubly linked list. | O(1)                   | O(1)                      | O(1)                          |
| `delete_at_beginning()`               | Deletes the first node in the doubly linked list. | O(1)                   | O(1)                      | O(1)                          |
| `delete_at_end()`                     | Deletes the last node in the doubly linked list. | O(1)                   | O(1)                      | O(1)                          |
| `remove(index)`                       | Removes the node at the specified index.  | O(n)                        | O(1)                      | O(1)                          |
| `Display()`                           | Displays the values of the doubly linked list. | O(n)                      | O(n)                      | O(1)                          |
| `insert(val, new_val)`                | Inserts a new node with the given value after the node with the specified value. | O(n)             | O(1)                      | O(1)                          |
| `insertatbegin(k)`                    | Inserts a new node with the given value at the beginning of the doubly linked list. | O(1)         | O(1)                      | O(1)                          |
| `insertatend(k)`                      | Inserts a new node with the given value at the end of the doubly linked list. | O(1)           | O(1)                      | O(1)                          |
| `insertatind(k, pos)`                 | Inserts a new node with the given value at the specified position in the doubly linked list. | O(n)    | O(1)                      | O(1)                          |
| `insert_after(value, new_value)`      | Inserts a new node with the given value after the node with the specified value. | O(n)             | O(1)                      | O(1)                          |
| `insert_before(value, new_value)`     | Inserts a new node with the given value before the node with the specified value. | O(n)            | O(1)                      | O(1)                          |

**Note:**
- Time complexity is given in terms of the number of nodes (n).
- Space complexity is specified for auxiliary space, not including the space required by the input and output.

Feel free to use this Doubly Linked List implementation for your projects and modify it as needed!
