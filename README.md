# Pathfinding Visualizer

This project's goal is to aid a mars rover powered by AI to find its path to it's destination.We use many algorithms in order to help the rover overcome the obstacles it faces and hence visualize the shortest path. Have a look at the project at https://pathfindervisualise.netlify.app/#

# Algorithms used

We have used 5 algorithms that use hueristics i.e are based on AI to help find shortest path,namely- A*,Greedy Best-first, Swarm, Convergent Swarm,Bidirectional Swarm,along with some other simple yet effecient algorithms such as dijkstra, bfs,dfs.Lets meet the algos used!

Dijkstra's Algorithm (weighted):for finding the shortest paths between nodes in a graph, which may represent, for example, road networks. ; GIVES SHORTEST PATH

A Search* (weighted): A* is a graph traversal and path search algorithm which uses heuristics, It is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency. One major practical drawback is its space complexity, as it stores all generated nodes in memory;  FASTER THAN DIJKSTRA; GIVES SHORTEST PATH

Greedy Best-first Search (weighted): Greedy best-first search algorithm always selects the path which appears best at that moment. It is the combination of depth-first search and breadth-first search algorithms. It uses the heuristic function and search. Best-first search allows us to take the advantages of both algorithms; FASTER THAN A* BUT NOT NECESSARILY GIVES GUARANTEE SHORTEST PATH

Swarm Algorithm (weighted): s a metaheuristic algorithm based on the concept of swarm intelligence capable of solving complex mathematics problems existing in engineering ;It is  mix of Dijkstra and A*; NOT NECESSARILY GIVES GUARANTEE SHORTEST PATH

Convergent Swarm Algorithm (weighted): the faster, more heuristic-heavy version of Swarm;  NOT NECESSARILY GIVES GUARANTEE SHORTEST PATH

Bidirectional Swarm Algorithm (weighted): Swarm from both sides; NOT NECESSARILY GIVES GUARANTEE SHORTEST PATH

Breadth-first Search (unweighted): ;Breadth-first search is an algorithm for traversing or searching tree or graph data structures. It starts at the tree root, and explores all of the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level; GIVES SHORTEST PATH

Depth-first Search (unweighted):Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking; NOT NECESSARILY GIVES GUARANTEE SHORTEST PATH


# Weighted Nodes
We can allocate weight to random nodes. It can be thought that the Grid is forest and the weight nodes are the "dense" portions while the others are lighter(preferred for easier movement).Hence the rover would try to avoid going through it when finding shortest path.However if it calculates that going through the weightnode is the only viable solution left, it will go through it as well!

# StopOver nodes
The stopOver node is added to the grid on clicking the button on navigation menu and can be dragged/moved at random positions.It can be thought of as the stop-over destination (fuel station etc) that the agent MUST visit before reaching the target/

# Mazes 
The web app also contains pre-defined mazes such as  Basic random maze,weighted maze,Step Maze etc to add a bit of fun element to the already existing mazes and seeing how our rover would navigate through it!

# Speed Setting
In addition to all of these amazing features we can also set the speed to viaualise the algorithm on a speed of our choice(Fast,Average,Slow) to have a deeper knowledge of the working of the algorithm.
