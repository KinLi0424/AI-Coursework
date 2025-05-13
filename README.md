# Maze Solver with Teleportation Links

This project is an implementation of the A* search algorithm to solve mazes with teleportation links. The project is divided into three main tasks:

## Tasks

### Task 1: Maze Solver with A* Algorithm
- Implemented the A* search algorithm to solve a randomly generated maze using the `mazelib` library.
- Teleportation links were introduced to allow jumps between specific cells, potentially reducing the pathfinding cost.
- The algorithm efficiently explores paths by evaluating the sum of the cost from the start node (g-cost) and the estimated cost to the goal (h-cost).

### Task 2: Analysis of Maze Size Impact
- Investigated the effect of maze size (n) on the number of steps required for the agent to find the goal.
- Fixed the number of teleportation links to 2 and experimented with maze sizes of 10, 15, 20, 25, and 30.
- Plotted the number of steps taken versus the maze size and discussed the algorithm's performance.

### Task 3: Analysis of Teleportation Links Impact
- Studied the impact of increasing teleportation links on pathfinding efficiency.
- Fixed the maze size to 30 and varied the number of teleportation links from 0 to 10.
- Analysed and plotted the effect on the number of steps to find the solution.

## Installation
To run the notebooks, install the dependencies:

```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/username/AI-Coursework.git
    cd AI-Coursework
    ```
2. Open the notebooks:
    ```bash
    jupyter notebook Task1.ipynb
    jupyter notebook Task2.ipynb
    jupyter notebook Task3.ipynb
    ```
3. Run the cells sequentially to see the maze generation, teleportation links, and pathfinding results.

## Results
- **Task 1:** Successfully navigated mazes with teleportation links using A*.
- **Task 2:** Pathfinding steps increased with larger maze sizes.
- **Task 3:** Teleportation links showed unpredictable behavior in optimizing paths.

## References
- Mazelib Library: [GitHub](https://github.com/john-science/mazelib)
- A* Search Algorithm: [AIMA Code](https://github.com/aimacode/aima-python)

## Future Work
- Optimizing teleportation link placement to enhance pathfinding efficiency.
- Exploring different maze generation algorithms for diverse path structures.
