# DSA Cheat Sheet

## Sliding Window
- Used when handling input data in a fixed window size.
- Helps optimize problems that involve subarrays or substrings.
- Avoids brute force by moving the window dynamically.

### Example Problems:
- [Longest Substring with K Distinct Characters](https://lnkd.in/ezaxRCdu)
- [Fruits into Baskets](https://lnkd.in/dzDPbRYS)

---

## Two Pointers
- Uses two pointers to traverse data, often from opposite directions.
- Helps optimize problems involving pairs, sorting, or merging.
- Reduces time complexity compared to brute force.

### Example Problems:
- [Squaring a Sorted Array](https://lnkd.in/eiivRjYX)
- [Dutch National Flag Problem](https://lnkd.in/efrJhnxS)

---

## Fast & Slow Pointers
- Also known as the Hare & Tortoise Algorithm.
- Uses two pointers moving at different speeds to detect cycles.
- Commonly used for linked lists and circular arrays.

### Example Problems:
- [Middle of the Linked List](https://lnkd.in/e5yt7isC)
- [Happy Number](https://lnkd.in/dFxNzx6X)

---

## Merge Intervals
- Deals with overlapping intervals.
- Used for scheduling, reservations, and range merging.
- Sorting intervals first usually helps in solving these problems.

### Example Problems:
- [Conflicting Appointments](https://lnkd.in/d29y9NDg)
- [Minimum Meeting Rooms](https://lnkd.in/dvegXkDJ)

---

## Cyclic Sort
- Used when elements fall within a fixed range.
- Helpful for finding missing or duplicate numbers in arrays.
- Uses in-place sorting instead of extra space.

### Example Problems:
- [Find All Missing Numbers](https://lnkd.in/dwYPm_Sh)
- [Find the First K Missing Positive Numbers](https://lnkd.in/dda-JKWz)

---

## In-Place Reversal of a Linked List
- Used to reverse the links between a set of nodes in-place.
- Often needs to be done without using extra memory.
- Works well for problems involving modifying linked list structure.

### Example Problems:
- [Reverse a Linked List](https://lnkd.in/ecPuKpU6)
- [Rotate a Linked List](https://lnkd.in/d7vrqjJR)

---

## Graphs
### Islands (Matrix Traversal)
- Used for traversing 2D grids or matrices efficiently.
- Commonly applies DFS or BFS for searching connected components.
- Helps solve problems related to islands, clusters, or paths.

### Example Problems:
- [Number of Islands](https://lnkd.in/eGSQncm8)
- [Flood Fill](https://lnkd.in/eRbcRFFu)

### Breadth-First Search (BFS)
- Traverses trees or graphs level by level.
- Used for finding shortest paths or exploring neighbors first.
- Implemented using a queue.

### Example Problems:
- [Binary Tree Level Order Traversal](https://lnkd.in/eXEdSMWv)
- [Minimum Depth of a Binary Tree](https://lnkd.in/dmitmppt)

### Depth-First Search (DFS)
- Traverses deep into trees or graphs before backtracking.
- Used for recursion-based traversal and path-related problems.
- Implemented using stack or recursion.

### Example Problems:
- [Path Sum](https://lnkd.in/eKfKJyg6)
- [Count Paths for a Sum](https://lnkd.in/e-fwAGBi)

### Topological Sort
- Solves problems involving dependencies between elements.
- Used for scheduling tasks or understanding dependency graphs.
- Often implemented using BFS or DFS.

### Example Problems:
- [Course Schedule](https://lnkd.in/eyXZFs2h)
- [Alien Dictionary](https://lnkd.in/eJ64NUJf)

---

## Shortest Path Algorithms
- **Dijkstra's Algorithm**
- **Bellman-Ford Algorithm**
- **Floyd Warshall Algorithm**
- **Union-Find Data Structure**

[Mastering Graph Algorithms](https://leetcode.com/discuss/study-guide/3900838/%22Mastering-Graph-Algorithms%3A-A-Comprehensive-DSA-Graph-Common-Question-Patterns-CheatSheet%22)

---

## Two Heaps
- Divides data into two halves: one for small elements, one for large ones.
- Uses Min-Heap and Max-Heap for quick median or priority access.
- Commonly used in streaming data or priority-based queries.

### Example Problems:
- [Find Median from Data Stream](https://lnkd.in/eewxqGtS)
- [Next Interval](https://lnkd.in/dimiArdU)

---

## Dynamic Programming
### Fibonacci Numbers
- Used for problems following a sequential dependency.
- Applies memoization or dynamic programming for optimization.
- Helps solve staircase problems, coin changes, and recursive dependencies.

### Example Problems:
- [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
- [House Robber](https://leetcode.com/problems/house-robber/)

### Palindromic Subsequence
- Solves problems involving palindromic sequences or substrings.
- Uses dynamic programming to break problems into smaller subproblems.

### Example Problems:
- [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/)
- [Minimum Insertions to Make a String Palindrome](https://leetcode.com/problems/minimum-insertion-steps-to-make-a-string-palindrome)

### Longest Common Subsequence
- Finds the longest matching sequence in strings or sequences.
- Uses Dynamic Programming or Hashing for optimization.

### Example Problems:
- [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)
- [Edit Distance](https://leetcode.com/problems/edit-distance/)

### 0/1 Knapsack
- Used for optimization problems with capacity constraints.
- Helps maximize profit while selecting items under limits.

### Example Problems:
- [Partition Equal Subset Sum](https://lnkd.in/emFwenrk)
- [Target Sum](https://lnkd.in/dsXUM9wF)

---

## Other Algorithms
### K-way Merge
- Merges multiple sorted arrays efficiently.
- Uses Heaps or Divide & Conquer for optimal merging.

### Example Problems:
- [Merge k Sorted Lists](https://lnkd.in/eAfqQmsc)
- [Kth Smallest Element in a Sorted Matrix](https://lnkd.in/dH22n5cW)

### Modified Binary Search
- Optimizes searching within a sorted dataset.
- Often leads to O(log N) complexity instead of brute force.

### Example Problems:
- [Find Peak Element](https://lnkd.in/d3p8QFBe)
- [Search in Rotated Sorted Array](https://lnkd.in/dK2piUNv)

### Bitwise XOR
- Uses the XOR operator for bit manipulation problems.

### Example Problems:
- [Single Number](https://lnkd.in/eNtF3DyD)
- [Missing Number](https://lnkd.in/e6Ag5k3N)

### Top K Elements
- [Top K Frequent Elements](https://lnkd.in/eFRyiuNw)
- [Kth Largest Element in an Array](https://lnkd.in/dztpqpuR)
