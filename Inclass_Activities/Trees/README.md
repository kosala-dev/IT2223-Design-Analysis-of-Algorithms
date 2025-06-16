
# MATLAB Tree Traversal Project

This project showcases how to construct a tree graph and perform fundamental graph traversal techniques using MATLAB. It is divided into three main sections:

## 1. Tree Construction and Visualization

In this section, a tree with three levels is created using MATLAB’s `digraph` function. Both unweighted and weighted versions of the tree are visualized. The nodes are labeled A to G, and edges represent parent-child relationships. The weighted version includes custom edge weights to illustrate how data can be embedded in the graph.

## 2. Breadth-First Search (BFS)

This section implements the Breadth-First Search algorithm. Starting from the root node, the algorithm explores all neighboring nodes at the current depth level before moving on to nodes at the next level. The order of traversal is recorded and displayed using node labels.

## 3. Depth-First Search (DFS)

This part demonstrates the Depth-First Search algorithm. Beginning at the root, the algorithm explores as far as possible along each branch before backtracking. A stack is used to manage traversal, and the visited node order is displayed.

## Requirements

- MATLAB (R2016b or later recommended)
- No additional toolboxes required

## Output

The output consists of tree plots and traversal orders printed in the command window for BFS and DFS.

## Author

This work was created for academic and demonstration purposes to understand basic graph operations and traversal techniques in MATLAB.

