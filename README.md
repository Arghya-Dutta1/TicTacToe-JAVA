# TicTacToe-JAVA
This is a CLI version of Tic Tac Toe game implemented using Java. In this version, the player competes against a computer, with the goal of aligning three of their symbols ('X' or 'O') in a row, column, or diagonal on a 3x3 grid. 

# Features
1. Player vs. Computer gameplay
2. Simple AI for computer moves (randomized valid moves)
3. Win detection for rows, columns, and diagonals
4. Tie detection if the board fills up without a winner

# How to Play
1. The game starts with an empty 3x3 grid.
2. The player is prompted to enter a number between 1 and 9, representing the position on the board where they wish to place their symbol ('X').
3. After the player's move, the computer will make a random valid move with its symbol ('O').
4. The game will check after each move whether the player or the computer has won, or if the game has ended in a tie.
5. The game continues until there is a winner or the board is full.


# Board Layout
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9

# Technologies Used
1. Java: The game is implemented using core Java.
2. Scanner Class: Used for handling user input.
3. Math.random(): Used for the computer to make random moves.

# Game Logic
The game checks for a winner after each move by evaluating all rows, columns, and diagonals. If one player has filled a line with their symbol, they win. If all 9 positions are filled without a winner, the game results in a tie

# Future Improvements
1. Add a more sophisticated AI that uses strategies (like blocking the player from winning).
2. Implement a graphical user interface (GUI) using libraries like Swing or JavaFX.
3. Add multiplayer functionality where two players can compete.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.
