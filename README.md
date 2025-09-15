Algo Pathfinder

Welcome to Algo Pathfinder!
I built this project because I was fascinated by pathfinding algorithms and wanted to see them in action. This tool helps visualize how different algorithms work step by step.

Algorithms Included

Dijkstra's Algorithm (weighted): Classic pathfinding; always guarantees the shortest path.

A Search* (weighted): One of the fastest and most accurate algorithms; uses heuristics to find the shortest path efficiently.

Greedy Best-First Search (weighted): Focuses heavily on heuristics; faster but doesn’t always give the shortest path.

Swarm Algorithm (weighted): A mix of Dijkstra’s and A*; does not guarantee the shortest path.

Convergent Swarm Algorithm (weighted): A faster, more heuristic-driven version of Swarm.

Bidirectional Swarm Algorithm (weighted): Runs Swarm from both the start and the target simultaneously.

Breadth-First Search (unweighted): Simple and reliable; guarantees the shortest path in unweighted grids.

Depth-First Search (unweighted): Explores deeply but is not good for shortest paths.

Maze Generation

The project also includes a Recursive Division maze generator, which creates interesting challenges for the algorithms to solve.

About the Swarm Algorithm

The Swarm Algorithm is something I co-developed with a friend. It’s like a hybrid of Dijkstra’s and A*:

It explores nodes around the start like Dijkstra’s.

At the same time, it moves toward the target like A*.

It balances both approaches by updating distances while using heuristics.

The result often looks like a “triangle” expanding toward the target. We named it Swarm because it mimics how a character in a game might chase a main boss while also keeping track of nearby enemies swarming around.

✨ You can make this even more engaging by adding animations, color codes for each algorithm, and side-by-side comparisons.
