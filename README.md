# Holberton School Sorting Algorithms Project

## Overview

This repository is dedicated to the Sorting Algorithms project, a component of the Holberton School curriculum that focuses on implementing and understanding various sorting techniques. Each algorithm is designed to rearrange a list of items into a specified order, often numerical or lexicographical, and is a fundamental concept in computer science for optimizing data handling and retrieval.

## Definition and Importance

Sorting algorithms organize data into meaningful orders to enhance the efficiency of other algorithms (like search and merge algorithms) that require sorted lists to function optimally. The performance of sorting algorithms is commonly evaluated using Big O notation, which measures the time complexity as the input size grows.

### Big O Notation

Big O notation describes the worst-case scenario of an algorithm's running time, helping developers understand the scalability and efficiency of their algorithms. For example:
- **O(n^2)**: Indicates that the running time increases quadratically with the input size.
- **O(n log n)**: Denotes that the running time increases log-linearly, typical for efficient sorting algorithms like mergesort and heapsort.

## Key Sorting Algorithms

This project covers a variety of sorting algorithms, each with specific use cases and efficiencies:

- **Bubble Sort**: A simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
- **Insertion Sort**: Builds the final sorted array one item at a time, suitable for small data sets or arrays that are already partially sorted.
- **Quick Sort**: An efficient, divide-and-conquer algorithm that picks an element as a pivot and partitions the array around the pivot.

### Usage Examples

Each sorting algorithm is implemented in C and includes a main file that demonstrates its usage. For instance, to run the bubble sort algorithm:

#```bash
gcc -Wall -Werror -Wextra -pedantic 0-main.c 0-bubble_sort.c print_array.c -o bubble_sort
./bubble_sort


### Part 4: Collaborators and Additional Information
#```markdown
## Collaborators

- **Mico Bledsoe** - GitHub: [@MicoBledsoe](https://github.com/MicoBledsoe)

## Additional Information

The repository includes utility functions such as `print_array` and `print_list` to help visualize the sorting process. It also provides comprehensive documentation for each sorting function, explaining the mechanics and best use cases.

## Compilation

All code should be compiled with:
#```bash
gcc -Wall -Werror -Wextra -pedantic *.c -o sort
