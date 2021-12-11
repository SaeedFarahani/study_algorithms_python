![](https://github.com/SaeedFarahani/study_algorithms_python/blob/main/graph/img/5205102925185024.svg)

## Breadth-first search (BFS)

BFS is an algorithm used for tree traversal on graphs or tree data structures.  
BFS can be easily implemented using recursion and data structures like dictionaries and lists.


**Time Complexity BFS**

Since all of the nodes and vertices are visited, the time complexity for BFS     
on a graph is O(V + E) where V is the number of vertices and E is the number of edges.

## Depth-first search (DFS)

The Algorithm

1. Pick any node. If it is unvisited, mark it as visited and recur on all its adjacent nodes.  
2. Repeat until all the nodes are visited, or the node to be searched is found.  

**Time Complexity**

Since all the nodes and vertices are visited, the average time complexity for DFS on a graph is O(V + E),  
where V is the number of vertices and E is the number of edges.  
In case of DFS on a tree, the time complexity is O(V), where V is the number of nodes.
