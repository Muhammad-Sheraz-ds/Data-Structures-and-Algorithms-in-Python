# Bubble Sort Algorithm

## Introduction

Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted. The algorithm is named for the way smaller or larger elements "bubble" to the top of the list.

## Algorithm

- Start with the first two elements of the list.
- Compare them and swap if the first is greater than the second.
- Move to the next pair of elements and perform the same operations.
- Continue these steps until the list is sorted.

## The time complexity of Bubble Sort is as follows:

- Best-case time complexity: O(n)
- Worst-case time complexity: O(n^2)

The space complexity is constant (O(1)) because Bubble Sort only requires a single additional memory space for storing a temporary variable during element swaps, regardless of the input size.

The best-case time complexity occurs when the list is already sorted, requiring n iterations through the list to verify and no swaps. The worst-case time complexity happens when the list is sorted in reverse order, necessitating n iterations for each element to move it to its correct position.


## Usage

The primary use of the Bubble Sort algorithm is to sort small lists or for educational purposes, as it's straightforward to understand and implement.
