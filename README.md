# Conways Game of Life

## Description

This is a simple implementation of Conway's Game of Life using HTML, CSS, and JavaScript. The game is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves.

## Installation

To get started with this project, clone the repository and open the `index.html` file in your browser.

## Usage

The game is played on a grid of cells, each of which can be in one of two possible states, alive or dead. Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
5. The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed—births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick.
6. The rules continue to be applied repeatedly to create further generations.

## Contributing

If you would like to contribute to this project, please open an issue or a pull request.