# OS Simulator Project

## Overview
This programming project is to simulate the CPU scheduling algorithms, banker’s algorithm, page replacement algorithms discussed in the class. You will write a program to implement a simulator with different algorithms. The program outputs a menu to the user, where the user selects his/her choice from the menu. In case of CPU scheduling algorithms, the simulator selects a task to run from ready queue based on the scheduling algorithm. Since the project intends to simulate a CPU scheduler, so it does not require any actual process creation or execution. When a task is scheduled, the simulator will simply print out what task is selected to run at a time. It outputs the way similar to Gantt chart style. The user can run any algorithm,

---

## Features
1. **CPU Scheduling Algorithms**:
   - **First Come First Serve (FCFS)**  
   - **Shortest Job First (SJF) Non-Preemptive**  
   - **Shortest Job First (SJF) Preemptive**  
   - **Round Robin (RR)**

2. **Deadlock Avoidance Algorithm**:
   - **Banker's Algorithm**: Computes safe sequences and validates resource requests.

3. **Page Replacement Algorithms**:
   - **First In First Out (FIFO)**
   - **Least Recently Used (LRU)**
   - **Optimal Replacement**

4. **Visualization**:
   - Gantt chart for scheduling algorithms using `matplotlib`.
   - Tabulated outputs for process, matrix, and page information.

---

## How to Run
### Prerequisites
- Python 3.x installed on your system.
- Required Python libraries:
  - `tabulate` for table formatting.
  - `matplotlib` for Gantt chart visualization.
