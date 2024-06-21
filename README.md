
# BFS Algorithms for Grid and Matrix Operations

Mark : 66/100


This repository contains various Python scripts demonstrating the use of Breadth-First Search (BFS) algorithms for operations on grids and matrices. These operations include flood fill, finding the largest connected component, and general traversal techniques. Below is a brief description of each file.

## Files

### Untitled6.ipynb

This Jupyter Notebook file includes multiple implementations of BFS for different tasks related to grid and matrix operations.

#### 1. Grid Class and BFS for Flood Fill

This section defines a `Grid` class and uses BFS to implement a flood fill algorithm. The flood fill algorithm changes the color of a region starting from a given point.

- **Class Definition**: Defines the `Grid` class to handle the grid structure.
- **Flood Fill Algorithm**: Uses BFS to change the color of all connected pixels of a given color starting from a specified point.

#### 2. Finding the Largest Connected Component

This section demonstrates how to find the largest connected component in a grid using BFS. The script calculates the size of the largest connected component of `0`s and `1`s in the grid.

- **Connected Component Search**: Uses BFS to traverse the grid and count the size of connected components.
- **Comparison**: Compares the sizes of connected components and identifies the largest one.

#### 3. Matrix Class and Flood Fill

This section defines a `Matrix` class and implements a flood fill algorithm using BFS. It traverses the matrix and records the size of the largest connected component.

- **Class Definition**: Defines the `Matrix` class to handle the matrix structure.
- **Flood Fill Algorithm**: Uses BFS to determine the size of the largest connected component starting from a given point.

## Requirements

To run these scripts, you need to have Python installed along with the necessary libraries. All required libraries are part of the Python standard library.

## Usage

To run any of the scripts, simply execute the script file using Python:

```bash
python <script_name>.py
