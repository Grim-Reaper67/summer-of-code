# DSA Learning and Practice

This repository contains my Data Structures and Algorithms learning work, LeetCode practice, Python solutions, report material, and video presentation slides.

The main focus of this work was not just to solve questions, but to understand why the solutions work, how different approaches compare, and how to write code that is readable, correct, and reasonably efficient.

---

## What This Repository Contains

This repository includes:

- Python solutions for LeetCode-style DSA problems
- Practice across easy and medium-level questions
- A endterm learning report in LaTeX
- A short video presentation slide deck with speaker notes
- Notes on theory, problem-solving approach, and key learnings

The code is written in a simple beginner-friendly Python style, with clear variable names and step-by-step logic.

---

## Topics Covered

The problems and report cover a wide range of DSA topics:

### Core DSA Topics

- Arrays and strings
- Frequency counting
- Prefix sums
- Sliding window
- Two pointers
- Sorting
- Binary search
- Stacks, queues, and deques
- Monotonic stack and monotonic deque
- Recursion and backtracking
- Binary trees
- Binary Search Trees
- Greedy algorithms
- Heaps and priority queues

### Dynamic Programming

Dynamic Programming was started from the basics and then extended to more types of problems.

Topics practised include:

- Basic 1D DP
- Climbing Stairs
- Min Cost Climbing Stairs
- House Robber
- House Robber II
- Decode Ways
- Unique Paths
- Minimum Path Sum
- DP on subsequences
- Coin Change
- Target Sum
- Partition Equal Subset Sum
- DP on strings
- Longest Common Subsequence
- Edit Distance
- Stock DP problems
- Grid-based DP problems

### Graphs

The later part of the work includes graph-based problems and graph algorithms such as:

- DFS
- BFS
- Multi-source BFS
- Flood Fill
- Number of Provinces
- Rotting Oranges
- 01 Matrix
- Surrounded Regions
- Number of Enclaves
- Topological sort
- Course Schedule
- Shortest path problems
- Dijkstra-style thinking
- Floyd-Warshall intuition
- Union-Find / Disjoint Set Union
- Kruskal and Prim's algorithm intuition

---

## Problem-Solving Approach

While solving the problems, I tried to follow this process:

1. Understand the input and output clearly.
2. Think of the brute-force solution first.
3. Check why the brute-force solution is correct.
4. Analyse its time and space complexity.
5. Identify repeated work or unnecessary operations.
6. Improve the approach using a suitable technique.
7. Write the solution in a clean and readable way.
8. Test edge cases.
9. Understand the final complexity.

A major part of the learning was realising that a correct solution is not always enough. A solution can still fail because of Time Limit Exceeded, Memory Limit Exceeded, invalid indexing, excessive recursion depth, or choosing the wrong data structure.

---

## Coding Style

The solutions are written in Python and follow a beginner-friendly style.

The code generally uses:

- descriptive `snake_case` variable names
- simple loops and conditions
- helper functions where needed
- clear intermediate variables
- readable logic over highly compressed code
- LeetCode-compatible `class Solution` formats where required

The aim was to write code that works and is easy to understand, rather than forcing the most optimised or shortest possible version.

---

## Learning Reflection

At the start, I was more comfortable with easy problems involving arrays, loops, dictionaries, sets, and basic recursion. Medium-level questions were much harder, especially when the required pattern was not obvious.

The biggest challenge was usually not writing Python syntax, but identifying the right approach. For example, recognising when to use a sliding window, monotonic stack, binary search on answer, DP state, BFS, DFS, or Union-Find took time.

I also learned that many algorithms are not meant to be memorised exactly. A big part of DSA is learning how to creatively modify a known algorithm for a new problem. For example:

- using BFS from multiple starting points instead of one
- changing binary search from searching an array to searching an answer
- adapting a stack to maintain a monotonic order
- defining a DP state differently depending on the constraint
- using Union-Find to group items that are indirectly connected

This was one of the more important parts of the learning process because many medium problems are not direct copies of standard examples.

---

## Theory Resources Used

The following Striver / take U forward playlists were used to study theory and understand the main DSA patterns:

- [Striver A2Z DSA Course](https://youtube.com/playlist?list=PLgUwDviBIf0oF6QL8m22w1hIDC1vJ_BHz&si=B06uryMr7D4SoBrv)
- [Recursion and Backtracking Playlist](https://youtube.com/playlist?list=PLgUwDviBIf0rGlzIn_7rsaR2FQ5e6ZOL9&si=k4poz2nzX1QUk0SW)
- [Dynamic Programming Playlist](https://youtube.com/playlist?list=PLgUwDviBIf0qUlt5H_kiKYaNSqJ81PMMY&si=5m3oq8XapQj9Gnnj)

The playlists were mainly used to build theory and intuition before or while solving problems. I used them to understand the reasoning behind algorithms, not just the final code.

---

## Report and Presentation

Along with solving problems, I prepared a learning report and a short video presentation.

The report discusses:

- topics learned so far
- important algorithms and concepts
- mathematical reasoning behind techniques
- time and space complexity
- correctness proofs and invariants
- real challenges faced while solving problems
- learning progress from easy to medium-level questions

The presentation summarises the topics learned and explains one problem in an interview-style format, including brute force, optimal approach, code walkthrough, and complexity analysis.
Video Presentation : [DP Problem](https://drive.google.com/file/d/1tjJldeJ7EoN7iDPXR5ejpW1icr4lyA4b/view?usp=sharing)

---

## Key Learnings

Some of the most important learnings were:

- Multiple solutions can exist for the same problem.
- Brute force is useful for understanding, even if it is not final.
- Constraints help decide the expected complexity.
- A solution must be checked for both time and memory.
- Sliding window and monotonic stack problems often need careful invariants.
- DP becomes easier when the state is clearly defined.
- Graph problems require clarity about direction, visited marking, and traversal order.
- Union-Find is useful for grouping connected components efficiently.
- Reading a solution is easier than independently identifying the pattern, so practice and tracing are important.

---

## Current Status

I am more comfortable with easy-level problems and basic implementations. Medium-level questions are still a work in progress, especially when multiple techniques are combined or when the main observation is not obvious.

The next goal is to practise more medium-level problems, reduce dependence on hints, and improve my ability to identify patterns independently.
