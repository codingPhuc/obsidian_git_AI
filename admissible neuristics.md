 An admissible heuristic is a heuristic function used in search algorithms that never overestimates the true cost of reaching the goal. In other words, it provides a lower bound estimate of the cost of reaching the goal from a given state. Admissible heuristics are important in search algorithms because they ensure that the algorithm will find the optimal solution, if one exists.

Admissible heuristics are commonly used in algorithms such as A* Search, which combines the benefits of breadth-first search and greedy best-first search. A* Search uses an admissible heuristic function to guide its search and determine which node to expand next. The heuristic function provides an estimate of the cost of reaching the goal from a given node, and the algorithm expands nodes in the order of their estimated total cost, with the node having the lowest estimated total cost being expanded first.

Examples of admissible heuristics include the Manhattan distance and the Euclidean distance between two points in a grid or on a map. In these cases, the heuristic function provides an estimate of the minimum number of moves required to reach the goal, taking into account the layout of the grid or map.

In conclusion, admissible heuristics play an important role in search algorithms, as they ensure that the algorithm will find the optimal solution, if one exists, and provide a lower bound estimate of the cost of reaching the goal.


## it is use in Manhattan 
The Manhattan distance, also known as the L1 distance, is a measure of the distance between two points in a grid-based space. It is calculated as the sum of the absolute differences of the coordinates between the two points.

Here is an example of how the Manhattan distance can be calculated between two points in a 2D grid:

Consider two points in a 2D grid, A (3, 4) and B (6, 2). To calculate the Manhattan distance between these two points, we find the absolute differences of each coordinate and add them together:

|3 - 6| + |4 - 2| = 3 + 2 = 5

So the Manhattan distance between points A and B is 5.

This example demonstrates how the Manhattan distance provides a measure of the minimum number of moves required to travel from one point to another in a grid-based space, taking