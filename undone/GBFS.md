#sumarize 
GBFS, or Greedy Best-First Search, is a search algorithm used in artificial intelligence and computer science. It is a variant of the Best-First Search algorithm and can be considered a heuristic search algorithm.

GBFS operates by expanding the node in the search tree that appears to be closest to the goal, based on an estimated cost function. This cost function can be thought of as an estimate of the distance from a given node to the goal. The algorithm expands nodes in the order of their estimated cost, with the lowest cost node being expanded first.

GBFS is often used in pathfinding and navigation problems, where the goal is to find the shortest path between two points. It is also used in other areas such as game playing, where it can be used to find the best move in a game.

Overall, GBFS is a useful search algorithm for problems where finding the optimal solution is not necessary, and a good approximation is sufficient.

## how does it work 
heuristic cost : this is


```mermaid  
d
```
A->E = 11 
B-> E = 8 
c-> E =4 
D-> E = 5
E-> E = 0 
h(x ) = 11 
## requirement of heuristic cost 
the heuristic cost must be  == to the actual cost 
- heuristic cost is the calucualated distind between a node  position and it goal post 
- actual cost is the distind between the node a it goal calcualted by it weight 
