# Tic-Tac-Toe Game

This is a simple command-line implementation of the classic Tic-Tac-Toe game written in C. The game allows two players to take turns marking spaces on a 3x3 grid, aiming to be the first to complete a row, column, or diagonal with their symbol.

## How to Play

1. **Compile the Code**: Compile the `tictactoe.c` source file using a C compiler such as GCC.
  
2. **Run the Game**: Execute the compiled program.

3. **Game Rules**:
   - Players take turns to input their moves by selecting a numbered block on the grid.
   - Player 1 is represented by 'X', and Player 2 is represented by 'O'.
   - The game continues until one player wins by filling a row, column, or diagonal with their symbol, or until the grid is full resulting in a draw.

4. **Display**: The game is displayed in the terminal with an updated grid after each move.

## Features

- **Clear Screen**: The screen is cleared after each move to provide a clean interface.
- **Input Validation**: Ensures that moves are within the valid range and on an empty block.
- **Win Detection**: Automatically detects when a player has won the game.
- **Draw Detection**: Checks for a draw if all spaces on the grid are filled without a winner.

## Compatibility

- The code is compatible with both Windows and Unix-based systems.
- It uses system-dependent commands for clearing the screen (`cls` for Windows and `clear` for Unix-based systems).
