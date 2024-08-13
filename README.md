# Tic Tac Toe Game

This is a simple Tic Tac Toe game built using Python's `tkinter` library. The game allows two players to take turns marking spaces in a 3x3 grid, with the goal of getting three marks in a row, column, or diagonal.

## Features

- **Two Player Mode**: Play against a friend in a classic Tic Tac Toe match.
- **Interactive GUI**: The game is played through a graphical user interface, allowing players to click on buttons to make their moves.
- **Winning and Tie Detection**: The game automatically checks for a winner or a tie after each move.
- **Automatic Board Reset**: After a game ends, the board is reset to start a new game.
- **Turn Switching**: The game alternates turns between player "X" and player "O".

## How It Works

1. **Initialization**: The game initializes a 3x3 grid of buttons using `tkinter`. Each button is associated with a command that handles the player's move.

2. **Gameplay**:
    - Players take turns clicking on the grid buttons to place their mark ("X" or "O").
    - After each move, the game checks if there is a winner by evaluating rows, columns, and diagonals.
    - If a player wins, a message box is displayed announcing the winner.
    - If all buttons are filled and there is no winner, the game announces a tie.

3. **Reset**: After a game concludes, whether by a win or a tie, the board is reset automatically, allowing the players to start a new game.

## Requirements

- Python 3.x
- `tkinter` library (usually included with Python installations)

## Running the Game

To run the game, save the code to a `.py` file (e.g., `tictactoe.py`) and execute it using Python:

```sh
python tictactoe.py
