# maze_solver
Minor project using java. Find the shortest path from source to destination in a maze using DFS

# Maze Solver: 
Find the shortest possible path between starting and ending point in a 2d grid.
White box: obstraction
Black box: movable path

# Features: 
1. Grids: Obstacles (1 in matrix) + freeblock(0 in matrix)
2. Starting point (1,1)
3. Ending point (9 in matrix)
4. Algo to find the path
5. GUI

# Technologies used:
1. Java (2d array traversal using DFS)
2. Java Swing(GUI)-> JFrame

#JFC (Java Foundation Classes): 
a set of GUI Components to simplify desktop app development.
#Java Swing: 
A part of JFC
1. used to create window based application
2. entirely written in Java
3. Lightweight components (like textLabel)
4. Platform independent

Java AWT(Abstract Windowing Toolkit): NOT USING
1. heavyweight, platform dependent, fewer components

JFrame: Window in which I can put desired components
Styling: Edge: red
FreeBolck: black (0 in matrix)
Obstruction: white (1 in matrix)
PathTaken: green

# ArrayTraversal: 
1. access every element in the array
Need: access and check if it is 0,1 or 9;

# DFS: 
algo to search in graphs, it reaches out far away from starting point, returns if it encounters a dead end or destination




