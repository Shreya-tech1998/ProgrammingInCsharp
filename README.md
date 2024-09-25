# ProgrammingInCSharp

This repository contains C# programming fundamentals, algorithms, data structures, and OOP concepts. Each section is structured to cover key topics comprehensively, ensuring a smooth learning path from basic syntax to advanced algorithms and design patterns in C#.

## Contents:

### 1. Introduction to Programming
#### a. BasicSyntax.cs
- **Topics to Cover**:
  - Variables and Data Types (`int`, `double`, `string`, `bool`)
  - Basic arithmetic operations
  - Simple method creation and usage
  - Console I/O (`Console.ReadLine()`, `Console.WriteLine()`)
  - Comments and code structure
- **Objective**: Provide an introduction to the syntax and fundamentals of C# programming.

#### b. ControlStructures.cs
- **Topics to Cover**:
  - Conditional statements: `if`, `else if`, `else`
  - Switch-case statements
  - Loops:
    - `for` loop
    - `while` loop
    - `do-while` loop
  - Nested control structures
  - Break and continue statements
- **Objective**: Teach how to control the flow of a C# program through conditionals and loops.

#### c. VariablesAndDataTypes.cs
- **Topics to Cover**:
  - Variable scope and lifetime (local and global variables)
  - Constants and `readonly` variables
  - Enumerations (`enum`)
  - Typecasting and conversions (`Convert.ToInt32()`, `int.Parse()`, explicit/implicit casting)
  - Nullable types
- **Objective**: Expand on data types, variable handling, type conversion, and nullable types.

---

### 2. Data Structures
#### a. Arrays/ArraysBasics.cs
- **Topics to Cover**:
  - Array declaration, initialization, and access
  - Single-dimensional and multi-dimensional arrays
  - Jagged arrays
  - Array traversal (for and foreach)
  - Array methods (`Array.Sort()`, `Array.Reverse()`)
- **Objective**: Introduce arrays and how to manipulate them in various ways.

#### b. Strings/StringManipulation.cs
- **Topics to Cover**:
  - String declaration and initialization
  - Common string methods (`Substring()`, `Replace()`, `IndexOf()`, `Trim()`, etc.)
  - String interpolation and concatenation
  - String comparison (`CompareTo()`, `Equals()`)
  - String immutability
- **Objective**: Demonstrate how to manipulate strings in C# and explain string immutability.

#### c. Dictionaries/DictionaryOperations.cs
- **Topics to Cover**:
  - Dictionary declaration and initialization
  - Adding, removing, and updating dictionary elements
  - Key-based lookup (`TryGetValue()`)
  - Iterating through dictionaries (`foreach`)
  - Dictionary performance considerations
- **Objective**: Provide a comprehensive introduction to dictionaries and their uses.

---

### 3. Sorting Algorithms
#### a. BubbleSort.cs
- **Topics to Cover**:
  - Bubble Sort algorithm (step-by-step explanation)
  - Code implementation of Bubble Sort
  - Time complexity analysis (`O(n^2)`)
- **Objective**: Implement and explain Bubble Sort, focusing on its simplicity and inefficiency for large data sets.

#### b. QuickSort.cs
- **Topics to Cover**:
  - Quick Sort algorithm (recursive partitioning)
  - Code implementation with pivot selection and recursive sorting
  - Time complexity analysis (`O(n log n)` best case, `O(n^2)` worst case)
- **Objective**: Introduce and explain Quick Sort, including its efficiency compared to Bubble Sort.

#### c. MergeSort.cs
- **Topics to Cover**:
  - Merge Sort algorithm (divide and conquer)
  - Recursive code implementation
  - Merging sorted subarrays
  - Time complexity (`O(n log n)`)
- **Objective**: Provide a divide-and-conquer approach to sorting.

#### d. SortingPerformanceAnalysis.md
- **Content**:
  - Compare time and space complexity of Bubble Sort, Quick Sort, and Merge Sort.
  - When to use each algorithm.
  - Practical performance insights based on input size and array structure.
- **Objective**: Offer a detailed performance comparison and guidance on algorithm selection.

---

### 4. Searching Algorithms
#### a. BinarySearch.cs
- **Topics to Cover**:
  - Binary Search algorithm (recursive and iterative versions)
  - Pre-requisite: sorted array
  - Time complexity analysis (`O(log n)`)
- **Objective**: Demonstrate efficient searching in a sorted array using Binary Search.

#### b. LinearSearch.cs
- **Topics to Cover**:
  - Linear Search algorithm
  - Code implementation and use cases
  - Time complexity (`O(n)`)
- **Objective**: Provide a simple implementation of Linear Search, comparing it to Binary Search.

#### c. SearchingComplexityAnalysis.md
- **Content**:
  - Compare the time complexity of Binary Search and Linear Search.
  - Discuss when each algorithm is appropriate.
  - Examples of real-world scenarios for each.
- **Objective**: Analyze the performance of searching algorithms based on array properties.

---

### 5. Big O Notation
#### a. BigOExplanation.md
- **Content**:
  - Explanation of Big O notation
  - Common time complexities (`O(1)`, `O(n)`, `O(log n)`, `O(n^2)`)
  - Examples of each complexity (e.g., constant time for access, linear time for loops, logarithmic time for binary search)
- **Objective**: Provide a theoretical explanation of Big O notation and time complexity.

#### b. BigOExamples.cs
- **Topics to Cover**:
  - Practical code examples demonstrating each time complexity:
    - `O(1)` for constant time (e.g., accessing an array element)
    - `O(n)` for linear time (e.g., traversing a list)
    - `O(log n)` for logarithmic time (e.g., binary search)
    - `O(n^2)` for quadratic time (e.g., nested loops)
- **Objective**: Implement real-world examples of different Big O complexities.

---

### 6. Common Algorithms
#### a. Recursion/Fibonacci.cs
- **Topics to Cover**:
  - Fibonacci sequence using recursion and iteration
  - Time complexity analysis (recursive version: exponential time `O(2^n)`)
  - Memoization to optimize recursive Fibonacci (`O(n)`)
- **Objective**: Teach recursion with Fibonacci and optimize it using memoization.

#### b. DivideAndConquer/MergeSort.cs
- **Topics to Cover**:
  - Recap of Merge Sort from `Sorting Algorithms`
  - Explanation of the divide-and-conquer paradigm (dividing a problem into subproblems)
- **Objective**: Reinforce the divide-and-conquer strategy using Merge Sort.

#### c. DynamicProgramming/KnapsackProblem.cs
- **Topics to Cover**:
  - 0/1 Knapsack Problem using dynamic programming
  - Bottom-up approach and memoization
  - Time complexity analysis (`O(nW)`)
- **Objective**: Provide a deep dive into dynamic programming using the Knapsack Problem.

---

### 7. Object-Oriented Programming (OOP)
#### a. ClassesAndObjects.cs
- **Topics to Cover**:
  - Defining classes and creating objects
  - Fields, properties, methods, and constructors
  - Object instantiation and method calls
- **Objective**: Provide a comprehensive introduction to classes and objects in C#.

#### b. InheritanceExample.cs
- **Topics to Cover**:
  - Inheritance in C# (base and derived classes)
  - Method overriding
  - `protected` access modifier
- **Objective**: Teach inheritance, method overriding, and code reuse through inheritance.

#### c. PolymorphismExample.cs
- **Topics to Cover**:
  - Polymorphism in C#
  - Method overloading and overriding
  - Use of `virtual` and `override` keywords
  - Dynamic (run-time) polymorphism using interfaces or base classes
- **Objective**: Demonstrate polymorphism and its applications in making code flexible and reusable.

---

## Author:
**Harsha Sai Jagu**
