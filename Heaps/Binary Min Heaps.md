# Min Binary Heap

A Min Binary Heap is a data structure representing a complete binary tree where the value at each node is less than or equal to its children's values. It's commonly used for priority queues, heap sort, and graph algorithms like Dijkstra's algorithm.

## Operations and Complexity

| Operation               | Best Case     | Worst Case     |
|-------------------------|---------------|----------------|
| Insert                  | O(1)          | O(log N)       |
| Extract Min             | O(1)          | O(log N)       |
| Delete by Index/Value   | O(log N)      | O(log N)       |
| Decrease Key            | O(log N)      | O(log N)       |
| Get Min                 | O(1)          | O(1)           |
| Shift Up                | O(log N)      | O(log N)       |
| Shift Down              | O(log N)      | O(log N)       |
| Build Heap              | O(N)          | O(N)           |
| Heap Sort               | O(N log N)    | O(N log N)     |

## Space Complexity

Space complexity is O(N), where N is the number of elements in the heap. This considers the space used by the elements and the heap structure itself.

## Application

- **Priority Queues**: Efficiently manage priorities and access elements with the highest priority.
- **Heap Sort**: Use the heap structure to sort elements efficiently.
- **Dijkstra's Algorithm**: Implement graph algorithms efficiently, such as finding the shortest path.

## Notes

- The complexities are based on standard binary heap operations and might vary based on the implementation details.
- Best-case scenarios involve operations near the root of the heap, while worst-case scenarios involve traversing through the height of the heap.
