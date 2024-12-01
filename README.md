# OS_Project
Overview
This project is a Python-based simulator for Operating System concepts. It demonstrates the functionality of various CPU scheduling algorithms, the Banker's Algorithm for deadlock avoidance, and page replacement algorithms. The program provides interactive inputs, calculates outputs, and visualizes results such as Gantt charts for scheduling.

Features
CPU Scheduling Algorithms:

First Come First Serve (FCFS)
Shortest Job First (SJF) Non-Preemptive
Shortest Job First (SJF) Preemptive
Round Robin (RR)
Deadlock Avoidance Algorithm:

Banker's Algorithm: Computes safe sequences and validates resource requests.
Page Replacement Algorithms:

First In First Out (FIFO)
Least Recently Used (LRU)
Optimal Replacement
Visualization:

Gantt chart for scheduling algorithms using matplotlib.
Tabulated outputs for process and page information.
How to Run
Prerequisites
Python 3.x installed on your system.
Required Python libraries:
tabulate for table formatting.
matplotlib for Gantt chart visualization.
Install dependencies using:

bash
Copy code
pip install tabulate matplotlib
Steps to Run
Download the OS_Simulator.py or .ipynb file.

If running a Python script:

bash
Copy code
python OS_Simulator.py
If using a Jupyter Notebook:

Open the .ipynb file in Jupyter Notebook or any compatible IDE.
Run the cells sequentially.
Follow the interactive menu to select the desired algorithm and input the required data.

Menu Options
On running the program, you'll be prompted to select from the following options:

CPU Scheduling Algorithms

Enter process details: arrival time, burst time, etc.
Observe calculated waiting and turnaround times.
Visualize the Gantt chart.
Banker's Algorithm

Input number of processes, resources, allocation matrix, max matrix, and available vector.
Observe the computed safe sequence and determine whether new resource requests can be granted.
Page Replacement Algorithms

Enter the number of frames and the page reference string.
Observe page faults, hit and miss ratios, and tabulated frame states.
Exit the program.
