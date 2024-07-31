# Conway's Game of Life

This project is a straightforward implementation of Conway's Game of Life using only JavaScript, HTML, and CSS. It avoids external libraries and canvas elements, opting instead to render the grid with an HTML table.

## Overview

Conway's Game of Life is a cellular automaton on a two-dimensional grid. It isn't a typical game with players but a simulation where each cell can either be alive or dead. Cells interact with their eight neighboring cells (in all directions, including diagonally) according to the following rules:

- A live cell with fewer than 2 live neighbors dies due to underpopulation.
- A live cell with 2 or 3 live neighbors continues to live.
- A live cell with more than 3 live neighbors dies due to overpopulation.
- A dead cell with exactly 3 live neighbors becomes alive through reproduction.

All cells are updated simultaneously in discrete time steps, known as generations or ticks. The game begins with an initial state known as the 'seed.'

## Features

- **No External Libraries:** Purely implemented in JavaScript, HTML, and CSS.
- **HTML Table Grid:** Utilizes an HTML table to display the grid.

## How to Run

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/conways-game-of-life.git
