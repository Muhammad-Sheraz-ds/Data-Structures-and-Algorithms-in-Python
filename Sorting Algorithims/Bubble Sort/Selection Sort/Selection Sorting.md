# Selection Sort Algorithm

## Introduction

Selection Sort is a simple sorting algorithm that divides the input list into two parts: the sorted part at the left end and the unsorted part at the right end. The algorithm selects the minimum element from the unsorted part and moves it to the beginning of the unsorted list, one element at a time. 

## Algorithm

- The algorithm starts by finding the minimum element in the unsorted part.
- It then swaps this minimum element with the leftmost unsorted element.
- The left side becomes sorted, and the right side becomes unsorted.
- The process continues, incrementally decreasing the size of the unsorted part until the entire list is sorted.



## Time and Space Complexity

### Time Complexity:
- Best Case: O(n^2)
- Worst Case: O(n^2)

### Space Complexity:
- Space: O(1)


## Advantages

- Simple and easy to implement.
- Efficient for small datasets.
- Minimal memory usage.

## Disadvantages

- Inefficient for large datasets.
- Performs unnecessary swaps.
- Slower compared to more optimized sorting algorithms.

## Usage

Selection Sort is primarily used for educational purposes or for small datasets due to its simplicity.

