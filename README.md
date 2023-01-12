# A-Star-Path-Finding-Visualization

A python visualization of the A-Star path finding algorithm. It allows you to pick your start and end locations, add obstacles, and view the process of finding the shortest path.

A* is a best-first search algorithm, meaning that it is formulated in terms of weighted graphs: starting from a specific starting node of a graph, it aims to find a path to the given goal node having the smallest cost (least distance travelled, shortest time, etc.). It does this by maintaining a tree of paths originating at the start node and extending those paths one edge at a time until its termination criterion is satisfied. At each iteration of its main loop, A* needs to determine which of its paths to extend. It does so based on the cost of the path and an estimate of the cost required to extend the path all the way to the goal.

Note: The heuristic function, h(n), that estimates the cost of the cheapest path from n to the goal has been implemented using the Manhattan distance method.

You can find the original author at [Tim Ruscica](https://github.com/techwithtim)
