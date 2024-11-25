# DAA-practical
Initialization:
Start with an empty MST 
T
T.
Select an arbitrary vertex 
u
u as the starting point.
Initialize a priority queue 
Q
Q to store edges with their weights, starting with all edges connected to 
u
u.
Process Edges:
While 
T
T has fewer than 
∣
V
∣
−
1
∣V∣−1 edges:
Extract the edge 
(
u
,
v
)
(u,v) with the minimum weight from 
Q
Q.
If 
v
v is already included in 
T
T, skip this edge.
Otherwise:
Add 
(
u
,
v
)
(u,v) to 
T
T.
Mark 
v
v as visited.
Add all edges from 
v
v to unvisited vertices to 
Q
Q.
Termination:
Stop when 
T
T contains 
∣
V
∣
−
1
∣V∣−1 edges.
Return MST:
The MST 
T
T is the set of edges collected during the process.
