#sumarize  
Hill climbing Algorithm is a local search algorithm which is used to find the peak of a mountain or the best solution to a problem by continuosly moving in the direction of increasing elevation 
## example 
we select a point to start at then move up to get thought the higest point in the local area 
 ![](../picture/Capture.png)
![](../picture/cáp.png)
## hill climbing algorithm flowchart 
```mermaid 
	flowchart TD 
	A['select current solutions S'] --> B['evaluate S']
	B --> S['select new solution X from neighborhood']
	S['evaluated X']--> D['is S better than X'] --no--> S
	D--yes-->F['select X as current solution']-->S
```
 