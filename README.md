# Sudoku Generator

<img src="https://img.shields.io/badge/GPL-v3-green"/>

Implementation of a genetic algorithm, through the **DEAP** framework, to generate a solved sudoku.   
The **fitness** function is proposed as a minimization problem, it consists of evaluating that the numbers in the rows, columns or sectors are not repeated, otherwise, the fitness is increased in one unit, so the ideal fitness for a solved sudoku is **0.0**.
