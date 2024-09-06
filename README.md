# Block-Cascade

This is a simple implementation of the classic Tetris game written in Java. The game features the standard Tetris mechanics, including seven different tetromino shapes, rotation, movement, line clearing, and scoring.

## Features

- **Seven Tetromino Shapes:** I, J, L, O, S, T, and Z pieces.
- **Piece Rotation:** The pieces can be rotated clockwise or counterclockwise.
- **Piece Movement:** Pieces can be moved left, right, or dropped down.
- **Line Clearing:** When a row is completely filled, it is cleared from the board, and the score is increased.
- **Scoring:** The game awards points based on the number of lines cleared simultaneously.

## How to Play

- **Rotate Piece:** Use the `Up Arrow` to rotate the piece counterclockwise and the `Down Arrow` to rotate it clockwise.
- **Move Left:** Use the `Left Arrow` to move the piece left.
- **Move Right:** Use the `Right Arrow` to move the piece right.
- **Drop Piece:** Press `Space` to drop the piece instantly to the bottom.

The game automatically drops the piece one step down every second.

## Running the Game

To run the game, you need to have Java installed on your machine. Follow these steps:

1. Compile the `Tetris.java` file:

   ```bash
   javac Tetris.java
