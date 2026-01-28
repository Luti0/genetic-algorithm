# genetic-algorithm

## Problem statement

A group of developers is working on a project. The entire project is divided into tasks, each task has a complexity category (1, 2, 3, or 4), and an estimated time to complete in hours. The project is considered complete when all tasks are finished. For each developer and each task complexity category, a coefficient is specified, which relates the actual time taken by the developer to complete the task to the estimated time. It is assumed that all developers start working on the project simultaneously and allocate the same amount of time for work. You need to implement a program that distributes tasks among developers to minimize the project completion time (achieve the completed project in the shortest possible time). The solution must be implemented using a genetic algorithm.

## Submission and Testing

The solution must be a text file containing the answer in the required format (when submitting, select the "Answer text" development environment in the testing system).
The solution earns points calculated using the following formula: $Score = \frac{10^6}{T_{max}}$. $T_{max}$ is the maximum time spent by any developer on completing the tasks assigned to them.

## Input File Format

- The first line of the input file contains an integer _N_ - the number of tasks.
- The second line contains _N_ integers _from 1 to 4_ representing the task complexity categories.
- The third line contains _N_ positive real numbers representing the estimated time for each task.
- The fourth line contains an integer _M_ - the number of developers.
- The next _M_ lines each contain 4 positive real numbers - the coefficients for each developer.

## Output File Format

The first and only line of the output file contains _N_ integer $w_i$ - the developer number assigned to the i-th task.
