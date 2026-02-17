AI Pathfinder – Uninformed Search Visualization
Description

This project is a visual AI Pathfinder built using Python and Pygame.
It demonstrates how different uninformed search algorithms explore a grid to find a path from a Start (S) point to a Target (T) point while avoiding walls.

Implemented Algorithms:

Breadth-First Search (BFS)

Depth-First Search (DFS)

Uniform-Cost Search (UCS)

Depth-Limited Search (DLS)

Iterative Deepening DFS (IDDFS)

Bidirectional Search

The visualization shows:

Frontier nodes

Explored nodes

Final path

Step count and statistics

Requirements

Python 3.12 (IMPORTANT: Pygame does not work properly on Python 3.14)

Pygame

Installation Instructions
1. Install Python 3.12

Download Python 3.12 from:
https://www.python.org/downloads/

Make sure to check:
"Add Python to PATH"

Verify installation:

python --version

It should show Python 3.12.x

2. Install Dependencies

Open Command Prompt inside the project folder and run:

pip install -r requirements.txt

This will install:
pygame

How to Run

Navigate to the project folder:

cd AI-Pathfinder

Run the program:

python pathfinder_algo.py

The game window will open.

Controls

Press 1–6 to select algorithm

S = Set Start

T = Set Target

SPACE = Run algorithm

C = Clear search

R = Reset grid

Drag mouse = Create walls

ESC = Exit
