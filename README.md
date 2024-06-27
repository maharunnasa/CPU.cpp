# Scheduling Algorithm with Gantt Chart

This is a C++ implementation of a scheduling algorithm that uses a priority queue to simulate the execution of processes, and outputs a Gantt chart representing the order of execution.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Contributing](#contributing)
- [License](#license)

## Overview

This program simulates the execution of processes with different priorities and CPU time requirements. It uses a priority queue to determine the order of execution and generates a Gantt chart to visualize the process scheduling.

## Requirements

- A C++ compiler (e.g., g++)
- Standard C++ library

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/maharunnasa/scheduling-algorithm.git
   cd scheduling-algorithm

*Code Explanation*
The code is structured as follows:

Constants:

cpu_lim: The time slice allocated to each process in each iteration.
lim: A variable used to manage process priorities in the priority queue.
Data Structures:

priority_queue<pair<pair<ll, ll>, string>> p: A priority queue to manage the processes.
map<string, ll> m: A map to store the remaining execution time for each process.
vector<pair<ll,string>> gantt_chart: A vector to store the Gantt chart data.
Main Function:

Initializes the priority queue with processes and their priorities.
Simulates the process execution using a priority queue and updates the Gantt chart accordingly.
Outputs the Gantt chart.



*Output of CPU*

----------------Gantt Chart-----------------
Time  : Character 
---> 2  Alice
---> 4  Alice
---> 6  Bob
---> 8  Eve
---> 10  Bob
---> 12  Charlie
---> 14  Charlie
---> 16  David
---> 18  David
---> 20  David
---> 22  David

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

