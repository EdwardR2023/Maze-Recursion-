**Magic Maze Solver**
This Java project comprises a maze-solving application capable of handling magic mazes with teleporters. It includes two main components: the MagicMaze class for solving the maze and the MagicMazeDriver class for driving the solving process.

**Overview**
The Magic Maze Solver is designed to solve mazes containing obstacles, open paths, and teleporters. It utilizes backtracking and dynamic programming techniques to explore possible paths through the maze, while also enforcing teleporter usage limits.

**Features**
Teleporter Handling: The solver properly handles teleporters, allowing traversal between connected teleporter pairs while enforcing usage limits.
Backtracking Algorithm: Utilizes backtracking to explore possible paths through the maze, ensuring all potential solutions are considered.
Command-line Interface: The driver program accepts command-line arguments specifying the maze file name, number of rows, and number of columns, making it easy to run and test different maze configurations.
Integration: The driver program integrates with the MagicMaze class to perform maze solving operations and output the pass/fail status.
**Usage**
Compile: Compile both the MagicMaze.java and MagicMazeDriver.java files.
Run: Execute the compiled MagicMazeDriver class with the following command:
javac MagicMazeDriver.java
java MagicMazeDriver [mazeFileName] [numRows] [numCols]
Replace [mazeFileName] with the name of the maze file, [numRows] with the number of rows in the maze, and [numCols] with the number of columns in the maze.

**Example:**
java MagicMazeDriver maze.txt 10 10
**Input Format**
The maze should be represented in a text file, where each character represents a cell in the maze. '@' denotes an obstacle, digits represent teleporters, and other characters represent open paths.
