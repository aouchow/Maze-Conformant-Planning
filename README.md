# Maze-Conformant-Planning

Solve a maze with the shortest path from multiple arbitrary starting points to an indicated goal. A movement sequence consists of relative movements up, down, left, right – moving to a blocked field results in non-movement. The simultaneous maze solving problem asks for the shortest movement sequence to the goal without knowing whether you started at which of the multiple starting point and without any sensory input. The program is completely sensorless in that it cannot tell whether it has hit a wall or when it has arrived at the goal.

Input: The program reads a grid maze that is represented as a matrix where fields containing a 0 are accessible while fields containing a 1 are blocked. Point G represents the goal. The grid maze input can also include additional information of starting points A and B.
