# Doubly Linked List

## Table of Contents

- [Description](#description)
- [Functions](#functions)
- [Time and Space Complexity](#time-and-space-complexity)
- [Contributing](#contributing)

## Description

A Doubly Linked List is a data structure that stores a collection of elements, each of which points to the previous and next elements in the sequence. This README provides an overview of the functions, time and space complexity analysis, and instructions for contributing to the project.

## Functions

### Append(value)

Add a value to the end of the linked list.

### Insert at Beginning(value)

Insert a value at the beginning of the linked list.

### Insert at Index(value, index)

Insert a value at a specific index in the linked list.

### Insert at End(value)

Insert a value at the end of the linked list.

### Update Node(value, index)

Update the value of a node at a specific index.

### Remove First Node

Remove the first node in the linked list.

### Remove Last Node

Remove the last node in the linked list.

### Remove at Index(index)

Remove a node at a specific index.

### Remove Node(value)

Remove a node with a specific value.

### Size of Linked List

Get the size (number of nodes) of the linked list.

### Display

Display the elements of the linked list.

### Iterator Functions

- Initialize an iterator at the head of the list.
- Initialize a reverse iterator at the tail of the list.
- Get the value of the current node in the iteration.
- Move the iterator to the next node in the forward iteration.
- Remove the current node being iterated.

# Time and Space Complexity

## Class Initialization (__init__(self))
- **Time Complexity**: O(1)
- **Space Complexity**: O(1)

The initialization method creates two sentinel nodes (head and tail) and sets them as the first and last elements in the list. This is a constant-time operation. Only two sentinel nodes are created regardless of the size of the list, so the space complexity is constant.

## Add Node (add_node(self, o))
- **Time Complexity**: O(1)
- **Space Complexity**: O(1)

Adding a node to the end of the list involves updating the prev and next pointers of the tail node and the new node. This is a constant-time operation. The space complexity is constant because only one additional node is created.

## Delete Node at Beginning (delete_at_beginning(self))
- **Time Complexity**: O(1)
- **Space Complexity**: O(1)

Removing the first node in the list involves updating the next pointer of the head node to point to the new first node. This is a constant-time operation. No additional data structures are created, so the space complexity is constant.

## Delete Node at End (delete_at_end(self))
- **Time Complexity**: O(1)
- **Space Complexity**: O(1)

Removing the last node in the list involves updating the next pointer of the second-to-last node to point to the tail node. This is a constant-time operation. No additional data structures are created, so the space complexity is constant.

## Remove Node by Index (remove(self, index))
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)

The time complexity of removing a node by its index depends on the position of the node to be removed. In the worst case, it may need to traverse the entire list, making it a linear time operation. No additional data structures are created, so the space complexity is constant.

## Insert Node by Value (insert(self, val, new_val))
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)

Inserting a node after a specific value requires traversing the list to find the value to insert after. In the worst case, it may need to traverse the entire list, making it a linear time operation. No additional data structures are created, so the space complexity is constant.

## Insert Node at Beginning (insertatbegin(self, k))
- **Time Complexity**: O(1)
- **Space Complexity**: O(1)

Inserting a node at the beginning involves updating the next and prev pointers of the new node, the current first node, and the head node. This is a constant-time operation. The space complexity is constant because only one additional node is created.

## Insert Node at End (insertatend(self, k))
- **Time Complexity**: O(1)
- **Space Complexity**: O(1)

Inserting a node at the end involves updating the next and prev pointers of the new node, the current last node, and the tail node. This is a constant-time operation. The space complexity is constant because only one additional node is created.

## Insert Node at a Specific Position (insertatind(self, k, pos))
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)

Inserting a node at a specific position requires traversing the list to find the insertion point. In the worst case, it may need to traverse the entire list, making it a linear time operation. No additional data structures are created, so the space complexity is constant.

## Insert Node after a Value (insert_after(self, value, new_value))
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)

Inserting a node after a specific value requires traversing the list to find the value to insert after. In the worst case, it may need to traverse the entire list, making it a linear time operation. No additional data structures are created, so the space complexity is constant.

## Insert Node before a Value (insert_before(self, value, new_value))
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)

Inserting a node before a specific value requires traversing the list to find the value to insert before. In the worst case, it may need to traverse the entire list, making it a linear time operation. No additional data structures are created, so the space complexity is constant.

## Display List (Display(self))
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)

Displaying the entire list requires traversing and printing all elements in the list, making it a linear time operation. No additional data structures are created for displaying the list, so the space complexity is constant.

## Traverse List (traverse(self))
- **Time Complexity**: O(n)
- **Space Complexity**: O(1)

Traversing the list to print its elements is a linear time operation, as it involves visiting all nodes. No additional data structures are created for traversal, so the space complexity is constant.

## Iterator Methods (begining(self), end(self), rbegining(self), rend(self))
- **Time Complexity**: O(1)
- **Space Complexity**: O(1)

These methods return iterators pointing to the head, tail, or sentinel nodes. They are constant-time operations. These methods return existing iterator objects, so the space complexity is constant.

## Iterator Methods (__iter__(self), __reversed__(self), getObject(self), __next__(self), remove(self))
- **Time Complexity**: O(1)
- **Space Complexity**: O(1)

These methods are used to create and manage iterators, so they are constant-time operations. These methods involve working with existing iterator objects, so the space complexity is constant.


## Contributing

Contributions are welcome! If you find any issues or have improvements to suggest, please open an issue or a pull request.
