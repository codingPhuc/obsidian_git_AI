the environement is  unpredictable in game 
- multiagent , unpredictatble : env 
- types : perfect info vs imperfect info 
- ADv search 
	- civers competitive environments in which the agents  goals are inconflict 
- zero sum game ( perfect)
	- deterministisc , fully observable environment , turn-taking , two player 
	- the utility values at the end are always equal and opposite 
- ninimax game : 
# programming 
- Complexity : game are to hard to be solved 
- Time limits : make some decision even when calculating the optimal decision is infeasible 
- Efficiency : penalize inefficiency severely
So - initial state : How the gamev is set up at the start 
player (s) : which plater has the move in a state  
Action(s) : successor function : A list of ( move , state) pair specifying legal move 
result (s,a) - Transition model : result of move a on state s 
Terminal -Test( s)  : is the game finished ? 
   - states where the gmae has ended are called terminal states 
Utility(s, p) - Utility funciont : a numbercal vlaue of

## optimal decision in games 
- Normal search problem 
	- optimal solution is a sequnece of action leading to a goal state 
 - gAMES 
	 - A search path that guarantee win for a player 
	 - The optimal strategy can be determined from the minimal vlaue of each node 
 minimax(x) = 
 
