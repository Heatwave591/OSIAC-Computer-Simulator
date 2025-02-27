# OSIAC Computer Simulator

This repository contains a simulator for the OSIAC computer, a simplified educational computer architecture.

## Overview

The OSIAC (One Step Intermediate Automatic Computer) simulator provides a platform to understand the fundamental principles of computer architecture and assembly language programming. It allows users to write and execute simple programs on a virtual machine that mimics the basic functionality of a real computer.

## Features

-   **Simulated OSIAC Architecture:** Implements the core components of the OSIAC computer, including the accumulator, memory, and instruction set.
-   **Assembly Language Support:** Enables users to write programs using a simplified assembly language tailored for the OSIAC architecture.
-   **Interactive Execution:** Provides an interactive environment to step through program execution, inspect memory, and observe the accumulator's state.
-   **Debugging Capabilities:** Offers basic debugging features to identify and resolve errors in your assembly language programs.

## Getting Started

### Prerequisites

-   Access to the OSIAC system developed by the Ohio State University.
-   A C++ compiler (e.g., GCC, Clang)
-   CMake (optional, for building from source)

### Building from Source (Optional)

1.  Clone the repository:

    ```bash
    git clone [https://github.com/Heatwave591/OSIAC-Computer-Simulator.git](https://www.google.com/search?q=https://github.com/Heatwave591/OSIAC-Computer-Simulator.git)
    cd OSIAC-Computer-Simulator
    ```

2.  Enter the Directory

    ```bash
    cd OSIAC-Computer-Simulator/MachineProblem1
    ```


### Running the Simulator

1.  Navigate to the directory containing the executable (either the build directory or the release directory).
2.  Run the simulator:

    ```bash
    ./dosim mp1-specs.dat test1
    ```
    Change the directory and file names accordingly

3. You should have a summary and a details file created in the same directory. That will be the required outputs for us.
