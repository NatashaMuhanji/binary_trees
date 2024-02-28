# Binary Trees and Binary Search Trees (BST)

This document provides a brief overview of binary trees and binary search trees (BST), including their differences, advantages in terms of time complexity compared to linked lists, and key characteristics such as depth, height, size, and traversal methods. Additionally, it covers different types of binary trees.

## Overview### What is a Binary Tree?

A binary tree is a data structure where each node has up to two children, known as the left child and the right child.

### Binary Tree vs. Binary Search Tree (BST)

- **Binary Tree:** Nodes are arranged without any specific order.
- **Binary Search Tree (BST):** A binary tree where for each node, all elements in the left subtree are less than the node, and all elements in the right subtree are greater, facilitating efficient searching.

## Time Complexity Advantages Over Linked Lists

- **Searching:** BST offers O(log n) search time complexity, more efficient than the O(n) in a linked list.
- **Insertion/Deletion:** BST operations can be more efficient on average compared to linear time operations in a linked list.

## Key Characteristics of a Binary Tree- **Depth of a Node:** Path length from the root to the node.
- **Height of a Tree:** Path length from the root to the deepest node.
- **Size of a Tree:** Total number of nodes.

## Traversal Methods1. **In-order (Left, Root, Right)**
2. **Pre-order (Root, Left, Right)**
3. **Post-order (Left, Right, Root)**
4. **Level-order (Breadth-First):** Traverse the tree level by level.

## Types of Binary

- **Complete Binary Tree:** Every level is fully filled, with all nodes as far left as possible.
- **Full Binary Tree:** Each node has either 0 or 2 children.
- **Perfect Binary Tree:** A full and complete tree where all leaves are at the same level.
- **Balanced Binary Tree:** The height difference between left and right subtrees of any node is no more than one.

