# Pathfinding-in-2D-maze
A GUI application for visualization of various pathfinding algorithm like<br>
`BFS, DFS, consistent A*, weighted A*, Greedy best first search, Bidirectional BFS`
build using C++ and [wxWidgets](https://github.com/wxWidgets/wxWidgets) (cross-platform GUI library).

Below is a demo of weighted A*

<img src="https://github.com/ankit-4129/Pathfinding-in-2D-maze/blob/main/demo.gif" alt="demo" width="590" height="300">

# How to Use
1. Use left mouse button to draw walls on grid(click and drag).
2. Use right mouse button to erase walls on grid(click and drag).
3. Click `Set Start` and then click(left mouse button) anywhere on grid to place "Start Point", Goal can be placed similarly.
4. Click `Clear All` to clear both walls and search path.
5. Click `Clear Search` to clear search path without erasing walls.
6. Use drop down to select algorithm.
7. Click `Start Simulation` to Start simulation.
8. To stop a running algorithm click `Stop Simulation`.
9. Random maze can be genrated by clicking `Genrate Random Maze` (random maze is genrated such that at least one path from start to goal always exsists).
10. `Nodes Explored` and `Solution Length` can be seen on side panel for comparing differnet algorithms.

# Run exe on Windows
for 64/32-bit system download and run [`maze x86.exe`](https://github.com/ankit-4129/Pathfinding-in-2D-maze/blob/main/maze%20x86.exe) around (7 MB)<br>
