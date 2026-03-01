# AI_Path_finding
# Pathfinding Visualizer (A* & Greedy Best-First Search)

This project is an interactive **Pathfinding Visualizer** implemented in **Python** using **Pygame**.  
It demonstrates heuristic-based search algorithms on a grid with real-time visualization, dynamic obstacles, and performance metrics.

---

## Features

- Algorithms:
  - A* (A-Star)
  - Greedy Best-First Search (GBFS)

- Heuristics:
  - Manhattan Distance
  - Euclidean Distance

- Interactive grid:
  - Click to add/remove obstacles
  - Random obstacle generation with adjustable density
  - Dynamic obstacle spawning during execution

- Agent simulation with automatic re-planning

- Metrics dashboard:
  - Nodes visited
  - Path cost
  - Execution time (ms)
  - Selected algorithm and heuristic

---

## Requirements

- Python **3.12** (recommended)
- pygame

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   (Recommended) Create and activate a virtual environment:

py -3.12 -m venv venv
venv\Scripts\activate

Install dependencies:

pip install pygame
How to Run

Run the program using:

python q6_AI.py
Enter the required values when prompted:

Rows (5–40)

Columns (5–60)

Obstacle density (0–0.9)

Controls
Keyboard

SPACE – Start / Pause agent

A – Switch algorithm (A* ↔ GBFS)

H – Switch heuristic (Manhattan ↔ Euclidean)

R – Reset agent

C – Clear all obstacles

Mouse

Click grid cells to toggle walls

Use on-screen buttons to control execution
Metrics Dashboard

Displayed in the bottom panel:

Nodes Visited

Path Cost

Execution Time (milliseconds)

Current Algorithm and Heuristic
