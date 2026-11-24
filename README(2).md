# Practical 1: Sorting Algorithms

This practical implements Selection Sort, Bubble Sort, and Merge Sort, insertion sort, quick sort 
Each algorithm includes implementation, time complexity analysis (best, worst, and average cases), and execution time measurement.

# Practical 2: Linear Search

This practical implements the Linear Search algorithm with interactive user input.
It demonstrates:
- Implementation of linear search that returns the index of the target (or -1 if not found).
- Measurement of execution time using `time.perf_counter()`.
- Time complexity analysis (Best, Average, Worst cases).

Usage:
- Interactive: run the script and follow prompts to provide the list and target value.
- Demo: run the script with a demo flag (if provided in the script).
1. linear search 
2. binary search 



# Practical 3: Max-Heap and Min-Heap Sort

Aim

To implement Min-Heap and Max-Heap Sort in Python.

Description
Min-Heap Sort: Sorts elements in ascending order.
Max-Heap Sort: Sorts elements in descending order.
Execution time is measured using time.perf_counter().
Time Complexity
Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n log n)
Conclusion

Min-Heap and Max-Heap Sort were successfully implemented to sort elements in ascending and descending order respectively.


# Practical 4: Factorial Using Iterative and Recursive Function
Description

This Python program calculates the factorial of a non-negative integer using two methods:

Iterative method Recursive method

It also compares the execution time and complexity of both methods.

Example

Input:

Enter a non-negative integer: 5

Output:

Number: 5

Iterative Method: Factorial: 120 Execution Time: 0.0000012000 seconds Time Complexity: O(n) Space Complexity: O(1)

Recursive Method: Factorial: 120 Execution Time: 0.0000015000 seconds Time Complexity: O(n) Space Complexity: O(n)

Complexity Method Time Space Iterative O(n) O(1) Recursive O(n) O(n) Requirements Python 3.x Run python factorial.py

Conclusion

Both methods produce the same factorial result. The iterative method uses less memory, while the recursive method demonstrates the use of recursion.


# pratical 7: Coin Change Problem Using Dynamic Programming

This project provides a Python solution to the Coin Change Problem using Dynamic Programming. The program determines the minimum number of coins required to make a given target amount from a set of available coin denominations.

The algorithm builds a dynamic programming table to store the minimum coins needed for every amount from `0` to the target value. By reusing previously computed results, it efficiently finds the optimal solution and avoids redundant calculations.

If the target amount can be formed, the program returns the minimum number of coins required. Otherwise, it returns `-1` to indicate that no valid combination exists.

### Features

* Efficient Dynamic Programming approach
* Finds the minimum number of coins required
* Handles impossible cases by returning `-1`
* Simple and easy-to-understand Python implementation

### Complexity

* **Time Complexity:** O(n × amount)
* **Space Complexity:** O(amount)

This project is useful for learning Dynamic Programming concepts, practicing algorithm design, and preparing for coding interviews.



# Pratical 8:Graph Implementation and Searching (DFS & BFS) in Python

## Overview
This practical demonstrates graph implementation using an **Adjacency List** and two graph traversal algorithms: DFS and BFS.

## Concepts Covered
- Graph Representation (Adjacency List)
- Depth First Search (DFS) – Uses Stack / Recursion
- Breadth First Search (BFS) – Uses Queue

## Technologies
- Python
- Collections (deque)

## Output

**DFS Traversal:**
```text
A B D E F C
```

**BFS Traversal:**
```text
A B C D E F
```

## Time Complexity
Both DFS and BFS: **O(V + E)**

## Learning Outcome
Learned graph representation and traversal using DFS and BFS.



# Practical 9 : Prim's Algorithm Implementation in Python

## Overview
This practical implements **Prim's Algorithm**, a greedy algorithm used to find the Minimum Spanning Tree (MST) of a connected, undirected, weighted graph.

## Concepts Covered
- Graph Representation (Adjacency List)
- Greedy Algorithm
- Minimum Spanning Tree (MST)
- Priority Queue (Min Heap)

## Technologies Used
- Python
- Heapq module

## Output
```text
Edges in the Minimum Spanning Tree:
A - B : 2
B - C : 1
B - D : 4
D - E : 2

Total weight: 9
```

## Complexity
- **Time Complexity:** O(E log V)
- **Space Complexity:** O(V + E)

## Learning Outcome
Learned how to implement Prim's Algorithm and find the Minimum Spanning Tree with minimum total edge weight.

