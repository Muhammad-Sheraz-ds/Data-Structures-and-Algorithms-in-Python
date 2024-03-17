# Binary Search Tree (BST) Implementation

This Python implementation provides a basic Binary Search Tree (BST) structure with various functionalities.

## Binary Search Tree (BST)

A Binary Search Tree (BST) is a binary tree data structure where each node has at most two child nodes, referred to as the left child and the right child. The key property of a BST is that the value of each node in the left subtree is less than or equal to the node's value, and the value of each node in the right subtree is greater than or equal to the node's value.

<div style="display: flex;">
<img style="width: 52%; height: auto;" src="../../Images/bst1.png">
<img style="width: 47%; height: auto;" src="../../Images/bst2.png">
</div>

## Class Structure

### Node
- **Attributes:**
  - `data`: The value of the node.
  - `left`: Reference to the left child node.
  - `right`: Reference to the right child node.

### BinSearchTree
- **Attributes:**
  - `root`: Reference to the root node.

## Functions and Time Complexity (Worst and Best Cases) and Space Complexity

| Function                     | Description                                      | Worst Case Time Complexity | Best Case Time Complexity | Space Complexity (Auxiliary) |
|------------------------------|--------------------------------------------------|----------------------------|---------------------------|-------------------------------|
| `insert(val)`                | Inserts a value into the BST.                    | O(h)                       | O(1)                      | O(1)                          |
| `Delete(val)`                | Deletes a node with a given value from the BST.  | O(h)                       | O(h)                      | O(1)                          |
| `search(val)`                | Searches for a node with a given value in the BST.| O(h)                       | O(1)                      | O(1)                          |
| `minValueNode(root)`         | Finds the node with the minimum value in the BST.| O(h)                       | O(1)                      | O(1)                          |
| `maxValueNode(root)`         | Finds the node with the maximum value in the BST.| O(h)                       | O(1)                      | O(1)                          |
| `height()`                   | Returns the height of the BST.                   | O(n)                       | O(n)                      | O(1)                          |
| `Display()`                  | Displays the nodes of the BST.                   | O(n)                       | O(n)                      | O(h)                          |
| `Inorder_Traversal()`        | In-order traversal of the BST.                   | O(n)                       | O(n)                      | O(h)                          |
| `Pre_Order_Traversal()`      | Pre-order traversal of the BST.                  | O(n)                       | O(n)                      | O(h)                          |
| `Post_Order_Traversal()`     | Post-order traversal of the BST.                 | O(n)                       | O(n)                      | O(h)                          |

**Note:**
- Time complexity is given in terms of the height of the tree (h) or the number of nodes (n).
- Space complexity is specified for auxiliary space, not including the space required by the input and output.

Feel free to use this Binary Search Tree implementation for your projects and modify it as needed!
