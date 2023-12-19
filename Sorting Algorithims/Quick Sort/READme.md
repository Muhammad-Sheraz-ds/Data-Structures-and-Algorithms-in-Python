# Quick Sort Algorithm

Quick Sort is a highly efficient sorting algorithm based on the principle of partitioning a list. It repeatedly selects a pivot element and partitions the array around the pivot, resulting in a sorted array. This algorithm follows a divide-and-conquer approach.

## Algorithm

1. **Select a Pivot:** Choose an element from the list (often the last element).
2. **Partitioning:** Rearrange the list so that elements less than the pivot are placed before it and elements greater are placed after it. The pivot element will be in its correct position.
3. **Recursively Apply:** Recursively apply the above steps to the sub-arrays on the left and right of the pivot.

## Usage

Quick Sort is commonly used in various programming languages and libraries due to its efficiency. It is often the preferred choice when sorting large datasets.

## Advantages

- Highly efficient for large datasets.
- Simple implementation.
- In-place sorting.

## Disadvantages

- Inefficient for small datasets.
- Unstable when implemented inefficiently.
- Possibility of stack overflow due to recursion for very large lists.

## Time and Space Complexity

**Time Complexity:**
- Best Case: O(n log n)
- Worst Case: O(n^2)
- Average Case: O(n log n)

**Space Complexity:**
- O(log n) - for the recursive call stack

Quick Sort is a powerful sorting algorithm that exhibits remarkable performance for large datasets, although it has some limitations for small datasets.
