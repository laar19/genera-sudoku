# Genera sudoku

Implementación de un algoritmo genético, mediante el framework **DEAP**, para generar un sudoku resuelto.   
La función **fitness** se plantea como un problema de minimización, consiste en evaluar que no se repitan los números en las filas, columnas ni sectores, de lo contrario, se incrementa en una unidad el fitness, por lo que el fitness idóneo para un sudoku resuelto es de **0.0**
