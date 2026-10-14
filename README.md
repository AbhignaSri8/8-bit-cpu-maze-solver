#  8-Bit CPU Maze Solver

An 8-bit CPU designed using **Logisim Evolution** to solve an 8×8 maze using Depth-First Search (DFS). This project explores how a processor can execute instructions, manage memory, and perform stack-based backtracking to navigate a maze.

##  Components

- **8-bit Datapath & ALU** — Performs arithmetic and logical operations.
- **Register File** — Stores temporary data during execution.
- **Program Counter & Instruction ROM** — Manage instruction execution.
- **Control Unit** — Coordinates CPU operations.
- **Maze RAM & Visited Memory** — Store the maze and track explored cells.
- **Stack Memory** — Supports backtracking during DFS.
- **FSM** — Controls stack operations.

##  How It Works

1. The CPU executes assembly-style instructions stored in instruction ROM.
2. It explores valid, unvisited cells in the maze using DFS.
3. Visited memory keeps track of explored cells.
4. Stack memory stores traversal information for backtracking when a dead end is reached.

##  Tools & Concepts

- Logisim Evolution
- Digital Logic Design
- Computer Organization & Architecture
- Assembly-Style Instructions
- Finite State Machines (FSM)
- Depth-First Search (DFS)

##  Project Status

- [x] Core CPU components designed and tested.
- [x] Selected instructions tested.
- [x] Memory structures designed for maze traversal.
- [ ] LED matrix maze visualization.
- [ ] Execution-cycle and memory-access analysis.

##  Project Structure

```text
8-bit-cpu-maze-solver/
├── README.md
├── cpu_maze_solver.circ
└── screenshots/
    └── system_architecture.png
```

##  Future Improvements

- Visualize maze traversal using an LED matrix.
- Measure execution cycles and memory accesses.
- Test the solver with different maze layouts.
- Optimize instruction execution.

##  Key Learning

Building a CPU from digital logic components and exploring how **processor architecture, memory management, and algorithmic problem-solving** work together to solve a practical problem.

---

*Built with curiosity and a passion for digital systems and hardware design.*
