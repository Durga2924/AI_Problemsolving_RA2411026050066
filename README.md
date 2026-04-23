# AI Problem Solving Projects

This repository contains two AI-based problem-solving projects:
1. GPS-Based City Route Finder using A* Algorithm
2. Interactive Game AI (Tic-Tac-Toe System)

---

## 1. GPS-Based City Route Finder (A* Algorithm)

### Problem Description
The objective of this project is to find the shortest path between two nodes (cities) using the A* (A-Star) search algorithm. The system simulates a GPS navigation system where nodes represent cities and edges represent distances between them.

---

### Algorithm Used
**A* Search Algorithm**

- Combines:
  - **g(n):** Actual cost from start node to current node
  - **h(n):** Heuristic cost (estimated distance to goal)
- Uses **Euclidean distance** as heuristic
- Ensures optimal and efficient pathfinding

---

### Execution Steps
1. Run the Python file
2. Enter the start node (e.g., A)
3. Enter the goal node (e.g., F)
4. The program calculates the shortest path using A*
5. Displays path and total cost

---

### Sample Output
GPS-Based Route Finder (A* Algorithm)
Available Nodes: ['A', 'B', 'C', 'D', 'E', 'F']

Enter Start Node: A
Enter Goal Node: F

Shortest Path Found:
A → B → E → F
Total Cost: 4


---

## 2. Interactive Game AI (Tic-Tac-Toe System)

### Problem Description
This project implements an intelligent Tic-Tac-Toe game where a human player competes against an AI. The AI always makes optimal moves to either win or draw the game.

---

### Algorithm Used
**Minimax Algorithm**

- Simulates all possible moves
- Chooses the move with the best outcome:
  - Win = +1
  - Draw = 0
  - Loss = -1
- Ensures AI never loses

---

### Execution Steps
1. Run the Tic-Tac-Toe Python file
2. Choose your symbol (X or O)
3. Enter positions (1–9) to make moves
4. AI responds automatically
5. Game continues until win/draw

---

### Sample Output
Tic-Tac-Toe Game

Player: X AI: O

1 | 2 | 3
4 | 5 | 6

7 | 8 | 9

Enter your move: 5

AI chooses position 1

Game Result: Draw


---

## Technologies Used
- Python
- Heap Queue (Priority Queue)
- Mathematical Heuristics
- Artificial Intelligence Algorithms

---

## Conclusion
These projects demonstrate the application of AI algorithms in:
- Pathfinding (A*)
- Game Decision Making (Minimax)

They provide a strong foundation for understanding real-world AI problem-solving techniques.

---