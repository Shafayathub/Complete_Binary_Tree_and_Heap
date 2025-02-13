# Complete Binary Tree and Heap in C++

This repository contains my practice code and implementations of **Complete Binary Tree** and **Heap** data structures in C++. The goal of this project is to understand the concepts, implement the data structures, and solve related problems.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Structures](#data-structures)
   - [Complete Binary Tree](#complete-binary-tree)
   - [Heap](#heap)
3. [Implementation Details](#implementation-details)
4. [Usage](#usage)
5. [Problems Solved](#problems-solved)
6. [Resources](#resources)
7. [Contributing](#contributing)

---

## Introduction
A **Complete Binary Tree** is a binary tree in which every level, except possibly the last, is completely filled, and all nodes are as far left as possible. A **Heap** is a specialized tree-based data structure that satisfies the heap property (either min-heap or max-heap). This repository explores these concepts and their implementations in C++.

---

## Data Structures

### Complete Binary Tree
- A binary tree where all levels are fully filled except possibly the last level.
- The last level is filled from left to right.
- Commonly used in implementing heaps.

### Heap
- A complete binary tree that satisfies the **heap property**:
  - **Max-Heap**: The value of each node is less than or equal to its parent.
  - **Min-Heap**: The value of each node is greater than or equal to its parent.
- Heaps are often used to implement priority queues.

---

## Implementation Details
The following C++ files are included in this repository:
1. **`CompleteBinaryTree.cpp`**: Implementation of a complete binary tree.
2. **`MaxHeap.cpp`**: Implementation of a max-heap.
3. **`MinHeap.cpp`**: Implementation of a min-heap.

Each implementation includes:
- Insertion
- Deletion
- Traversal (e.g., level-order traversal)
- Utility functions (e.g., checking if the tree/heap is valid)

---

## Usage
To compile and run the code:
```bash
g++ CompleteBinaryTree.cpp -o CompleteBinaryTree
./CompleteBinaryTree

g++ MaxHeap.cpp -o MaxHeap
./MaxHeap

g++ MinHeap.cpp -o MinHeap
./MinHeap