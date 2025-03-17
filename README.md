# Data-Structures-&-Algorithms-Implementations
Implemented Data Structures from scratch in C++

## Contents
- Overview
- Files
- How It Works
- Usage
- Example Execution
- Notes
- License

## Overview
This project contains various C++ exercises implementing different data structures and algorithms. Each file corresponds to a specific exercise focusing on sorting, linked lists, trees, and graph algorithms. These implementations help reinforce fundamental concepts in algorithm design and data structure manipulation.

## Files

### 1. Sorting Algorithms - Ex1
- Implements **Selection Sort** and **Heap Sort**.
- Reads a vector of integers and sorts them using both methods.

### 2. Linked List Sorting - Ex4
- Implements a basic **linked list** where words are inserted and sorted alphabetically.
- Uses **Node-based structure** for storing elements.

### 3. Singly Linked List - Ex21
- Implements **a singly linked list** with append, print, search, and delete operations.
- Supports inserting elements at a given position.

### 4. Doubly Linked List - Ex22
- Implements **a doubly linked list** with bidirectional traversal.
- Allows insertion and deletion at any position.

### 5. Circular Doubly Linked List - Ex23
- Implements **a circular doubly linked list**.
- Supports append, print, search, and erase operations.

### 6. Circular Singly Linked List - Ex24
- Implements **a circular singly linked list**.
- Supports append, print, search, and erase operations.

### 7. Parentheses Matching - Ex31
- Uses a **stack-based approach** to check if parentheses are balanced in a string.

### 8. Next Greater Element in an Array - Ex32
- Uses **stack and queue structures** to determine the next greater element for each array element.

### 9. Binary Search Trees (BST) and Merging - Ex51
- Implements **BST creation, merging, and traversal**.
- Sorts and merges two BSTs.
- Finds BST keys within a given range.

### 10. Minimum Spanning Tree (MST) with Prim’s Algorithm - Ex61
- Implements **Prim’s Algorithm** to find the Minimum Spanning Tree of a weighted graph.
- Uses adjacency matrix representation.

### 11. MST with a Greedy Approach - Ex62
- Implements a **greedy algorithm** for constructing a Minimum Spanning Tree.
- Uses a **Boolean array** to track visited nodes and selects the smallest edge iteratively.
- Outputs the selected edges and their costs.

## How It Works
- The files contain various implementations of sorting, linked lists, tree structures, and graph algorithms.
- Each program reads input from the console, processes the data using relevant algorithms, and outputs the results.
- Some programs utilize **dynamic memory allocation** for linked lists and **recursion** for tree-based operations.

## Usage
### Running the Programs
To compile and run any of the `.cpp` files, use:
```bash
g++ filename.cpp -o filename
./filename
```

### Expected Input
Each program prompts the user for input based on the problem being solved. Example:
```
Cate elemente in vector?
6
5 2 4 1 3 6
```

## Example Execution
### Sorting Example - Ex1
#### Input:
```
6
5 2 4 1 3 6
```
#### Output:
```
Ex1a: 1 2 3 4 5 6
Ex1b: 1 2 3 4 5 6
```

### Parentheses Matching - Ex31
#### Input:
```
{[()]}
```
#### Output:
```
1 (valid parentheses)
```

### MST Greedy Algorithm - Ex62
#### Output:
```
Muchie <-> Cost
(0, 1) <-> 1
(3, 1) <-> 2
(4, 3) <-> 3
(2, 3) <-> 5
```

## Notes
- Programs require standard C++ compilers like **g++**.
- Ensure valid input formats to avoid runtime errors.
- Memory management is handled using **malloc/free** or `new/delete` where necessary.

## License
This project is free to use and modify for educational purposes.

