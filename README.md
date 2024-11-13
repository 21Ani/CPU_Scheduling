

# CPU Scheduling Simulator

This **CPU Scheduling Simulator** project implements various CPU scheduling algorithms using **Java**. The program allows users to simulate and analyze the behavior of different scheduling algorithms by providing them with input for multiple processes, such as burst time, arrival time, and priority. 

The project uses **Object-Oriented Programming (OOP)** principles, providing an easy-to-understand and extendable structure for managing processes and implementing scheduling algorithms.

## Algorithms Implemented:
1. **First-Come, First-Served (FCFS)** - A non-preemptive algorithm that executes processes in the order of their arrival times.
2. **Shortest Job First (SJF)** - A non-preemptive algorithm where the process with the smallest burst time is executed first.
3. **Round Robin (RR)** - A preemptive algorithm that gives each process a fixed time quantum in cyclic order.
4. **Priority Scheduling** - A non-preemptive algorithm that schedules processes based on their priority levels (lower priority value indicates higher priority).

## Features:
- **User Input**: Accepts user input for the number of processes, burst time, arrival time, and priority for each process.
- **Scheduling Simulation**: Simulates the behavior of the selected scheduling algorithm based on the provided data.
- **Results Calculation**: Calculates and displays the **waiting time** and **turnaround time** for each process, as well as the **average waiting time** and **average turnaround time**.
  
## Usage:
1. Clone the repository or download the source code to your local machine.
2. Compile and run the program using your preferred Java environment.
3. Input the number of processes and their respective burst times, arrival times, and priorities.
4. Choose the scheduling algorithm you want to simulate (FCFS, SJF, Round Robin, or Priority).
5. The program will output the waiting time, turnaround time, and averages for each process.

## Example:
```bash
Enter the number of processes: 3
Enter details for Process 1:
Burst Time: 5
Arrival Time: 0
Priority: 1
Enter details for Process 2:
Burst Time: 3
Arrival Time: 2
Priority: 2
Enter details for Process 3:
Burst Time: 4
Arrival Time: 4
Priority: 1
Select Scheduling Algorithm:
1. FCFS
2. SJF
3. Round Robin
4. Priority Scheduling
```

## How to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/21Ani/CPU-Scheduling-Simulator.git
   ```

2. Navigate to the project directory and compile the Java file:
   ```bash
   javac Main.java
   ```

3. Run the program:
   ```bash
   java Main
   ```

4. Follow the prompts in the terminal to input your process details and select the scheduling algorithm.


