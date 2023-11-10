# Max Binary Heap

## Introduction
A Max Binary Heap is a specialized tree-based data structure that satisfies the heap property – in a Max Heap, for any given node C with parent P, the value of P is greater than or equal to the value of C. It's commonly represented as an array.

## Purpose
The primary application of the Max Binary Heap is in implementing priority queues and the Heap Sort algorithm. It efficiently finds the maximum element and allows quick insertion, deletion, and retrieval of maximum elements.

## Time and Space Complexities

| Operation               | Best Case     | Worst Case     |
|-------------------------|---------------|----------------|
| Insert                  | O(1)          | O(log N)       |
| Extract Max             | O(1)          | O(log N)       |
| Delete by Index/Value   | O(log N)      | O(log N)       |
| Increase Key            | O(log N)      | O(log N)       |
| Get Max                 | O(1)          | O(1)           |
| Shift Up                | O(log N)      | O(log N)       |
| Shift Down              | O(log N)      | O(log N)       |
| Build Heap              | O(N)          | O(N)           |
| Heap Sort               | O(N log N)    | O(N log N)     |

### Space Complexity
Space complexity is O(N) where N is the number of elements in the heap.

This README provides an introduction to the Max Binary Heap, its core operations, and their respective time and space complexities.
