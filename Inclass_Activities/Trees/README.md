
# MATLAB Tree Traversal Project

This project showcases how to construct a tree graph and perform fundamental graph traversal techniques using MATLAB. It is divided into three main sections:

## 1. Tree Construction and Visualization

In this section, a tree with three levels is created using MATLAB’s `digraph` function. Both unweighted and weighted versions of the tree are visualized. The nodes are labeled A to G, and edges represent parent-child relationships. The weighted version includes custom edge weights to illustrate how data can be embedded in the graph.

![SimpleTree](https://github.com/user-attachments/assets/03242ad5-0aa5-4c47-90a2-6994da7905b4)
![WeightedTree](https://github.com/user-attachments/assets/048d0c32-e545-4139-89c6-4c2770e73d2e)


## 2. Breadth-First Search (BFS)

This section implements the Breadth-First Search algorithm. Starting from the root node, the algorithm explores all neighboring nodes at the current depth level before moving on to nodes at the next level. The order of traversal is recorded and displayed using node labels.

<img width="959" alt="BFS" src="https://github.com/user-attachments/assets/9dd74de7-310b-4f1d-b43e-eed4c74ccafd" />


## 3. Depth-First Search (DFS)

This part demonstrates the Depth-First Search algorithm. Beginning at the root, the algorithm explores as far as possible along each branch before backtracking. A stack is used to manage traversal, and the visited node order is displayed.

<img width="959" alt="DFS" src="https://github.com/user-attachments/assets/0d3b21d1-74ba-46d6-b28b-68beb6f25b94" />


## Requirements

- MATLAB (R2016b or later recommended)

