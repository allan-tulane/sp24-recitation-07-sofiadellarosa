# CMPS 2200 Recitation 10## Answers

**Name:** Sofia Della Rosa
**Name:** Jaimie Morris


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**  
  Work of reachable (assuming n nodes and m edges) = O(M + N) since each vertex and edge are visited once. 
- **4)**
  worst case number of times we need to call reachable to determine if a graph is connected = once, because all of the nodes are visited in calling reachable 

- **5)**
  work of connected = O(M + N)

- **7)** it would change the work of reachable. It would primarily change how neighbors are accessed because in an adjacency matrix each row would be individually scanned. This would change the work to O(n^2) because it would represent neighbors as an n*n matrix
