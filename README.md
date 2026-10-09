# Drone Delivery Path Planner Using Dijkstra's Algorithm

## Project Description
A C-based application that finds the shortest path for a drone to travel from a starting point to a destination while avoiding obstacles. It uses Dijkstra's algorithm to calculate the shortest path and Depth-First Search (DFS) to display up to three possible routes.

## Features
- Custom grid size and input
- Obstacle avoidance
- Shortest path calculation using Dijkstra's algorithm
- Display of up to three possible routes using DFS
- Shortest distance calculation

## Technologies Used
- Programming Language: C
- Algorithms: Dijkstra's Algorithm and Depth-First Search (DFS)

## Grid Symbols
- `.` — Free path
- `X` — Obstacle
- `S` — Starting point
- `D` — Destination
- `*` — Path marker

## How to Run
1. Install GCC on your computer.
2. Download `main.c` from this repository.
3. Open a terminal in the folder containing the file.
4. Compile the program:

   `gcc main.c -o main`

5. Run the program on Windows:

   `main.exe`

## Project Objective
To demonstrate the application of graph algorithms in drone navigation, obstacle avoidance, and shortest-path planning.
