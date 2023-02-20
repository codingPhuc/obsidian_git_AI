#sumarize  
	- backtracking is the process  of trying out the value in each domain one at a time and if it break the contraint problem the programme will then blacktrack and return to it pevious state
- backtracking involves assigning values to variables one at a time, in a depth-first search manner, until a solution is found
- enhanced with additional techniques such as forward checking, arc consistency, and heuristics.
- Backtracking can be a computationally expensive algorithm, particularly for large search spaces.
- Its flexibility and generality make it a popular algorithm for solving a wide range of combinatorial problems.
#execution  
let say that we have three different domain 
A ,B, C 
A domain have {1,2,3}
b have {1,2,3} 
C have {1,2,3}
[[CONSTRAINT SATISFACTION PROBLEM]]
A>B
B!= C 
A!= C
| A   | B   | C   | backtrack |
| --- | --- | --- | --------- |
| 1   | 1   |     | yes       |
| 1   | 2   |     | yes       |
| 1   | 3   |     | yes       |
| 2   | 1   | 1   | YES       |
| 2   | 1   | 2   | YES       |
| 2   | 1   | 3   | NO        |

#CONCUSION 
SO IF WE REACH A STATES IN THE AVARIBLE DOMAIN THAT SATISFIED THE [[CONSTRAINT SATISFACTION PROBLEM]] WE END THE PROGRAM 
-> backtraking can be implemented with [[DFS]]
## improving backtracking 
 var order : most constrained var 
	- minimum remaining var 
	- most contraining var
 value order : 
	 -least constranning value 
	

