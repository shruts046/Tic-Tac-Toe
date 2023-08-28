# Tic-Tac-Toe Game in Python
This repository contains a simple implementation of the classic game **Tic-Tac-Toe** using Python. The game is designed to be played in the command line interface. Players take turns to enter their moves, and the game checks for a win or a draw condition after each move.

_**How to Play**_

1. Clone the Repository:
git clone https://github.com/your-username/tic-tac-toe.git
cd tic-tac-toe

2. Run the Game:
python tic_tac_toe.py

3. Gameplay:
- The game board consists of a 3x3 grid, where players will enter their moves as position numbers.
- Players alternate turns, and each turn, a player specifies a position number (1-9) where they want to place their move (X or O).
- The game checks for a win condition or a draw after each move. If a player wins or the game ends in a draw, the game will display the result.

_**Code Overview**_

The implementation consists of the following components:
1. display(row1, row2, row3): This function is responsible for displaying the current state of the game board.
2. win(): This function checks if there's a win condition on the game board, such as three X's or three O's in a row, column, or diagonal.
3. Game Loop: The game is played within a loop that continues until either a player wins or the game ends in a draw. Players take turns entering their moves, and the game board is updated accordingly.
4. Player Input Validation: The game ensures that players only enter valid position numbers (1-9) and prevents invalid inputs.

_**Example Run**_

Here's an example of how the game would be played:

1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9
---------

Player 1's turn (X)
Enter the position number where you would like to play your move: 5
Please play your move X | O: X

1 | 2 | 3
---------
4 | X | 6
---------
7 | 8 | 9
---------

Player 2's turn (O)
Enter the position number where you would like to play your move: 2
Please play your move X | O: O

1 | O | 3
---------
4 | X | 6
---------
7 | 8 | 9
---------

...

Player 1 wins!

_**Conclusion**_
This simple Python implementation of Tic-Tac-Toe provides a basic introduction to coding a two-player game and handling player input. Have fun playing!
