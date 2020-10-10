# Breadth First Search Algorithm<br>

The breadth first search algorithm is a very famous algorithm that is used to traverse a tree or graph data structure. It is guaranteed to find the shortest path from a start node to an end node if such path exists. This algorithm can be used for a variety of different tasks but for this example we will use it to solve a maze.<br>

# How it Works <br>

In short the breadth first search algorithm creates a set of all possible routes and attempts each one until it finds the end node. It is a queue based algorithm. It is **extremely inefficient** and is not ideal for large data structures. Once the algorithm finds a path that reaches the end node it is guaranteed that this is the shortest possible path. This is because of the queue structure that the algorithm uses.<br>

[](https://github.com/everydaycodings/Path-Finding-With-Breadth-First-Search-Algorithm/blob/master/E8gB.gif)<br>

# Path Finding With Breadth First Search<br>

One of the common applications of breadth first search is to perform path finding. Typically this is done in a 2D maze. The code below implements the breadth first search algorithm to traverse and find the shortest path out of a maze.<br>