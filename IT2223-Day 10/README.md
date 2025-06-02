
# MATLAB Algorithms and Graph Visualization

This repository contains three MATLAB scripts demonstrating sorting algorithms and graph plotting using MATLAB's built-in functions.

## Contents

1. **Merge Sort Implementation** (`Merge_Sort.m`)
2. **Quick Sort Implementation** (`Quick_Sort.m`)
3. **Graph Plotting** (`Graphs.m`)

---

## 1. Merge Sort (`Merge_Sort.m`)

A recursive implementation of the **Merge Sort** algorithm that divides the array into halves, sorts them individually, and merges the results.

### Features:
- Uses recursion and helper `merge()` function
- Handles arrays of arbitrary length

### Example:
```matlab
Original array:
    45     7    89    41    23    12

Sorted array:
     7    12    23    41    45    89
```

---

## 2. Quick Sort (`Quick_Sort.m`)

This script implements the **Quick Sort** algorithm using a divide-and-conquer strategy.

### Features:
- Uses the first element as a pivot
- Partitions the array into `left`, `equal`, and `right`
- Recursively sorts and concatenates the results

### Example:
```matlab
Original Array:
    45    12    39    74   100

Sorted Array:
    12    39    45    74   100
```

---

## 3. Graph Plotting (`Graphs.m`)

This script demonstrates basic and weighted graph creation using MATLAB's `graph` object and `plot()` function.

### Features:
- Constructs simple undirected graphs
- Adds weights to edges and visualizes them using labels

### Example Output:
- First plot shows a simple undirected graph
- Second plot displays a weighted graph with edge labels

---

## How to Run

1. Open MATLAB.
2. Run each `.m` file individually to see outputs and visualizations:
   - `Merge_Sort.m`
   - `Quick_Sort.m`
   - `Graphs.m.m`

---

## Requirements

- MATLAB (any recent version supporting `graph` and basic plotting functions)

---