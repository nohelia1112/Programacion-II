# Conway’s Game Of Life

The “game” is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves, or, for advanced “players”, by creating patterns with particular properties.

## How the game works
Because the Game of Life is built on a grid of nine squares, every cell has eight neighboring cells, as shown in the given figure. A given cell (i, j) in the simulation is accessed on a grid [i][j], where i and j are the row and column indices, respectively. The value of a given cell at a given instant of time depends on the state of its neighbors at the previous time step.

## Rules
Conway’s Game of Life has four rules:
 
- If a cell is ON and has fewer than two neighbors that are ON, it turns OFF
- If a cell is ON and has either two or three neighbors that are ON, it remains ON.
- If a cell is ON and has more than three neighbors that are ON, it turns OFF.
- If a cell is OFF and has exactly three neighbors that are ON, it turns ON.

[<img align="center" alt="Figure1" width="250px" src="https://media.geeksforgeeks.org/wp-content/uploads/20201102133039/GameOfLifeDiagram.png" />](https://www.geeksforgeeks.org/conways-game-life-python-implementation/)

<br />

*Source: https://www.geeksforgeeks.org/conways-game-life-python-implementation/*

---

# Juego de la Vida

El "juego" es un juego de cero jugadores, lo que significa que su evolución está determinada por su estado inicial, que no requiere más entrada. Uno interactúa con el Juego de la Vida creando una configuración inicial y observando cómo evoluciona, o para “jugadores” avanzados, creando patrones con propiedades particulares. 

## Funcionamiento del juego
Debido a que el Juego de la Vida está construido sobre una cuadrícula de nueve cuadrados, cada celda tiene ocho celdas vecinas, como se muestra en la figura dada. Se accede a una celda determinada (i, j) en la simulación en una cuadrícula [i][j], donde i y j son los índices de fila y columna, respectivamente. El valor de una celda dada en un instante de tiempo dado depende del estado de sus vecinos en el paso de tiempo anterior.

## Reglas
El Juego de la Vida de Conway tiene cuatro reglas:

- Si una celda está encendida (ON) y tiene menos de dos vecinos que estén encendidos, se apaga (OFF).
- Si una celda está ON y tiene dos o tres vecinos que están ON, permanece ON.
- Si una celda está ON y tiene más de tres vecinos que están ON, se convierte OFF.
- Si una celda está OFF y tiene exactamente tres vecinos que están ON, se convierte ON.

[<img align="center" alt="Figure1" width="250px" src="https://media.geeksforgeeks.org/wp-content/uploads/20201102133039/GameOfLifeDiagram.png" />](https://www.geeksforgeeks.org/conways-game-life-python-implementation/)

<br />

*Fuente: https://www.geeksforgeeks.org/conways-game-life-python-implementation/*
