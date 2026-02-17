# AI Pathfinder – Uninformed Search Visualization

## Overview

AI Pathfinder is a visual pathfinding project built using **Python** and **Pygame**.  
It demonstrates how different uninformed search algorithms explore a grid to find a path from a **Start (S)** node to a **Target (T)** node while avoiding obstacles.

This project visually shows how each algorithm expands nodes, manages its frontier, and determines the final path.

---

## Implemented Algorithms

- **Breadth-First Search (BFS)**
- **Depth-First Search (DFS)**
- **Uniform-Cost Search (UCS)**
- **Depth-Limited Search (DLS)**
- **Iterative Deepening Depth-First Search (IDDFS)**
- **Bidirectional Search**

---

## Features

- Visualization of frontier nodes  
- Visualization of explored nodes  
- Final path highlighting  
- Start and target node selection  
- Wall/obstacle placement  

---

## Technologies Used

- **Python 3.12**
- **Pygame**

---

## Installation and Setup

### Important Python Version Note

This project requires **Python 3.12**.

Pygame may not work properly with **Python 3.14**, so make sure you are using Python 3.12 before installing dependencies.

You can check your Python version with:

```bash```
py --version

## Install Python 3.12

If needed, install Python 3.12 from:  
[https://www.python.org/downloads/release/python-3120/](https://www.python.org/downloads/release/python-3120/)

## Install Dependencies

Install Pygame using Python 3.12:

````bash```
py -3.12 -m pip install pygame


Verify installation:

```bash```
py -3.12 -m pip show pygame


**Running the Project**

Run the project using Python 3.12:

```bash ```
py -3.12 "c:/Users/aman1/OneDrive/Documents/python codes/ai_ass1.py"


## How It Works

1. Generate the grid.  
2. Select a Start (`S`) node.  
3. Select a Target (`T`) node.  
4. Add walls/obstacles.  
5. Choose an algorithm. Watch the visualization as the algorithm finds the path.
