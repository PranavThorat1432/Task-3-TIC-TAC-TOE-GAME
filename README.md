# Tic-Tac-Toe Game in C++

Welcome to the Tic-Tac-Toe Game repository! This project implements a simple Tic-Tac-Toe game in C++ where you can play against the computer.

## Features

- **Game Board**: A 3x3 grid for the game.
- **Players**: Play as `X` against the computer (`O`).
- **Display Board**: Shows the current state of the board.
- **Player Input**: Prompts the player to enter their move.
- **Update Board**: Updates the board with the player's move.
- **Check for Win**: Checks if the current player has won.
- **Check for Draw**: Determines if the game is a draw.
- **Switch Players**: Alternates turns between the player and the computer.
- **Display Result**: Shows the result of the game (win, draw, or ongoing).
- **Play Again**: Option to play another game after the current game ends.

## How to Play

1. Follow the prompts to enter your move by selecting a spot (1-9). The game will display the current state of the board after each move.

2. The computer will make its move, and the game will continue until there is a winner or a draw.

3. After the game ends, you will be asked if you want to play again. Enter `y` to play another game or `n` to exit.


## Code Overview

- **main()**: Initializes the game, manages the game loop, and handles player input for playing again.
- **drawBoard()**: Displays the current state of the game board.
- **playerMove()**: Handles the player's move input and updates the board.
- **computerMove()**: Generates a move for the computer and updates the board.
- **checkWinner()**: Checks if there is a winner and displays the appropriate message.
- **checkTie()**: Checks if the game is a draw and displays the appropriate message.
- **switchPlayer()**: Switches the current player.


Happy playing!
