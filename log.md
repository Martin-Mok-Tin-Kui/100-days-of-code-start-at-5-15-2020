### Day 1: May 15, Friday

**Today's Progress**: I am solving the Cash Register on FreeCodeCamp.

**Thoughts**: I've used a lot of time testing how to calculate the change array. I learn how to use the while loop or Math.min(denomination,total/denomination) to directly calculate the correct change for each denomination as in real life. And, the most important part is how to get rid of the javascript precision loss with Math.round(x*100)/100 or Math.floor!

**Link to work**
1. [Cash Register](https://gist.github.com/Martin-Mok-Tin-Kui/880a4ddd1fbf7e810b878db2c36ce675)  

**Reference**
1. [freeCodeCamp Challenge Guide: Cash Register
](https://www.freecodecamp.org/forum/t/freecodecamp-challenge-guide-cash-register/16012)  
2. [Solving FreeCodeCamp.org’s Final Project Challenge: Cash Register](https://medium.com/@chyanpin/solving-freecodecamp-orgs-final-project-challenge-cash-register-d6ecb941d966)  

### Day 2: May 16, Saturday

**Today's Progress**: I try to implement the Depth-first search to find all the paths from one node to another in an undirected graph.

**Thoughts**: I've tried to understand when to use differnet graph representation: Edge lists, Adjacency matrices and Adjacency lists. Use integer as graph labeling. Tried to implement recursive Depth-first search without the need to use stack. Keep a visited node list so as to prevent cyclic recursion of the program.

**Link to work**
1. [web-soln1](https://github.com/Martin-Mok-Tin-Kui/programming-test/blob/master/web%20soln/web-soln1.md)  

**Reference**
1. [Data Structures in JavaScript: Graphs](https://medium.com/better-programming/basic-interview-data-structures-in-javascript-graphs-3f9118aeb078)  
2. [Representing graphs](https://www.khanacademy.org/computing/computer-science/algorithms/graph-representation/a/representing-graphs)

### Day 3: May 17, Sunday

**Today's Progress**: Implemented the recursive Depth-first search to find all the paths in an undirected graph, that each node can only be visited once in each path.

**Thoughts**: I used javascript Map of Set to create the adjacency list for the graph, and used an allPath array to store the paths. The dfs start at any chosen node and eventually find all the paths with the constraint that the end node is the node that all the neighbours were visited. The base case for terminating the recursion is that the current node have no unvisited neighbours.

**Link to work**
1. [find-all-path-of-a-graph-with-DFS](https://github.com/Martin-Mok-Tin-Kui/programming-test/blob/master/web%20soln/find-all-path-of-a-graph-with-DFS.md)  

**Reference**
1. [Data Structures in JavaScript: Graphs](https://medium.com/better-programming/basic-interview-data-structures-in-javascript-graphs-3f9118aeb078)  
2. [Print all paths from a given source to a destination](https://www.geeksforgeeks.org/find-paths-given-source-destination/)  

### Day 4: May 18, Monday

**Today's Progress**: 

**Thoughts**: I used javascript Map of Set to create the adjacency list for the graph, and used an allPath array to store the paths. The dfs start at any chosen node and eventually find all the paths with the constraint that the end node is the node that all the neighbours were visited. The base case for terminating the recursion is that the current node have no unvisited neighbours.

**Link to work**
1. [find-all-path-of-a-graph-with-DFS](https://github.com/Martin-Mok-Tin-Kui/programming-test/blob/master/web%20soln/find-all-path-of-a-graph-with-DFS.md)  

**Reference**
1. [Data Structures in JavaScript: Graphs](https://medium.com/better-programming/basic-interview-data-structures-in-javascript-graphs-3f9118aeb078)  
2. [Print all paths from a given source to a destination](https://www.geeksforgeeks.org/find-paths-given-source-destination/)  
