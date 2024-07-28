# Tic-Tac-Toe Game

This is a simple console-based Tic-Tac-Toe game implemented in C++. Two players take turns to enter their moves and the game checks for a win or a draw after each move.

## How to Play

1. Run the program.
2. Players will be prompted to enter their move by specifying a number from 1 to 9 that corresponds to the positions on the board.
3. The game will update the board and check if a player has won or if the game is a draw.
4. The game will continue until either a player wins or all positions are filled resulting in a draw.

## Game Board

The board is represented as follows at the start of the game:

```
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9
```

Players will enter the number corresponding to the position they wish to place their mark ('X' or 'O').

## Code Explanation

The main components of the code are:

- `printBoard()`: Prints the current state of the board.
- `checkWin(char player)`: Checks if the specified player has won the game.
- `isDraw()`: Checks if the game is a draw.
- `makeMove(char player)`: Prompts the current player to make a move.
- `main()`: The main game loop that runs the game, alternating turns between players until there is a win or a draw.

## Example Gameplay

```
Player X, enter your move (1-9): 1
X | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9

Player O, enter your move (1-9): 5
X | 2 | 3
---------
4 | O | 6
---------
7 | 8 | 9

...

Player X wins!
```

## Contact

For any questions or feedback, please contact [Salman Khalid](mailto:m.salmankhalid123@gmail.com).

---

By Salman Khalid
```
