# ALGORITHM BATTLE – WHICH DATA STRUCTURE WINS?

## Student Record Search System

**Course:** Data Structures and Algorithms  
**Institution:** SRM Institute of Science and Technology, Tiruchirappalli  
**Assignment:** Continuous Learning Assessment – 2 (CLA-2)

## Project Overview

This project implements and compares three important data structures for efficient student record searching:

1. Binary Search Tree (BST)
2. AVL Tree
3. Hashing with Linear Probing

The application stores student records using unique Student IDs and allows efficient insertion and searching.

## Objectives

- Implement BST for student record management.
- Implement AVL Tree with automatic balancing.
- Implement Hashing using Linear Probing.
- Perform successful and unsuccessful searches.
- Compare search comparisons, tree heights and hash collisions.
- Identify the most suitable data structure based on experimental observations.

## Technologies Used

- Programming Language: Python
- Data Structures: BST, AVL Tree and Hash Table
- Collision Handling: Linear Probing
- Version Control: Git and GitHub

## Project Structure

```text
Algorithm-Battle-DSA/
│
├── src/
│   └── main.py
│
├── README.md
├── REPORT.md
├── requirements.txt
├── sample_run_output.txt
└── .gitignore
```

## Features

- Insertion of student records
- Successful searching
- Unsuccessful searching
- BST inorder, preorder and postorder traversal
- AVL Tree balancing using rotations
- Hash collision handling using Linear Probing
- Performance comparison of all three data structures

## How to Run

1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Open the terminal.
4. Execute:

```bash
python src/main.py
```

## Experimental Analysis

The same dataset of 40 unique student records is used for all three data structures.

The experiment compares:

- Number of search comparisons
- BST and AVL tree heights
- Hash collisions
- Insertion performance
- Successful and unsuccessful searches

## Time Complexity Comparison

| Operation | BST Average | AVL | Hashing Average |
|---|---|---|---|
| Searching | O(log n) | O(log n) | O(1) |
| Insertion | O(log n) | O(log n) | O(1) |

*BST worst-case complexity is O(n), AVL worst-case is O(log n), and hashing worst-case is O(n).*

## Conclusion

Hashing with Linear Probing is recommended for applications requiring fast exact Student ID searches. AVL Tree is suitable when balanced searching and sorted traversal are important. BST provides a simple implementation but may become unbalanced depending on insertion order.

## Author

**Aswin-2008**

## Academic Project

Submitted as part of the Continuous Learning Assessment – 2 (CLA-2), Data Structures and Algorithms.
