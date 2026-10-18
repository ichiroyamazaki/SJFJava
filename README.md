# SJFJava

A Java-based application that demonstrates the Shortest Job First (SJF) CPU scheduling algorithm with a Gantt chart.

SJFJava helps students understand how operating systems schedule processes based on their CPU burst times. The Gantt chart provides a visual representation of the execution order and duration of each process.

Developed by Ichiro Yamazaki in January 2024, this project is intended for educational use and operating systems coursework.

## Features

- Shortest Job First Scheduling: Organizes eligible processes based on CPU burst time.
- Gantt Chart Visualization: Displays the process execution sequence and time intervals.
- Process Scheduling: Demonstrates how the SJF algorithm selects processes for execution.
- Java Compatibility: Runs in a compatible Java environment.
- Educational Application: Helps students learn CPU scheduling concepts.

## Requirements

- Java Runtime Environment (JRE) compatible with the application.
- Java Development Kit (JDK) if compiling the source code.
- A Java-compatible IDE, such as IntelliJ IDEA, Eclipse, or NetBeans, if modifying the source code.
- The project source files.

Use a Java version compatible with the project's source code and compiled classes.

## Installation and Setup

### 1. Install Java

Install a compatible Java release from a trusted Java distribution.

Verify your installation:

```bash
java -version
```

If compiling from source, verify that the Java compiler is available:

```bash
javac -version
```

### 2. Open the Project

1. Open your preferred Java-compatible IDE.
2. Import or open the project directory.
3. Configure the appropriate JDK.
4. Set the main class if necessary.
5. Build and run the application.

### 3. Compile and Run from the Command Line

If the project contains a standalone source file named `SJFJava.java`, use:

```bash
javac SJFJava.java
java SJFJava
```

If the project contains multiple source files or packages, adjust the commands to match the repository structure.

## How SJF Scheduling Works

Shortest Job First selects the eligible process with the shortest CPU burst time.

In non-preemptive SJF scheduling, the selected process runs until completion. When all processes arrive at time zero, they can be arranged in ascending order of burst time.

For example:

| Process | Burst Time |
|---|---:|
| P1 | 6 |
| P2 | 2 |
| P3 | 4 |

The execution order is P2, P3, then P1.

```text
0       2           6               12
|  P2   |    P3     |       P1       |
```

This example assumes non-preemptive SJF scheduling and that all processes are available at time zero. Actual behavior depends on the implementation.

## Project Information

- Project Name: SJFJava
- Programming Language: Java
- Algorithm: Shortest Job First (SJF)
- Visualization: Gantt Chart
- Developer: Ichiro Yamazaki
- Build Date: January 2024
- Project Category: Operating Systems and CPU Scheduling

## Disclaimer

This project is intended for educational purposes. Scheduling behavior, input options, and displayed results depend on the implementation included in the source code.

## License

No license has been specified. All rights are reserved by the respective copyright holder unless a license is added to this repository.
