### Title:TIC TAC TOE GAME
TicTacToe is a command-line game written in Java that allows two players to play the classic game of Tic-Tac-Toe. The game board is a 3x3 grid where players take turns placing their marks ('X' or 'O') until one player wins or the game ends in a draw.

### Features

  * **Command-line Interface:** The game is played directly in the console.
  * **Player Turns:** The game alternates between Player 'X' and Player 'O'.
  * **Win Detection:** The game automatically detects a winning combination in rows, columns, or diagonals.
  * **Draw Detection:** The game can identify when the board is full and the game is a draw.
  * **Input Validation:** The game validates player input to ensure moves are made on empty and valid spaces.

### How to Run

1.  **Compile:** Compile the `TicTacToe.java` file using a Java compiler.
    ```bash
    javac TicTacToe.java
    ```
2.  **Run:** Execute the compiled class file.
    ```bash
    java TicTacToe
    ```

### How to Play

1.  The game will display the initial empty 3x3 board.
2.  Player 'X' starts first and is prompted to enter a row and column (0-2).
3.  Enter the row number, press enter, and then enter the column number.
4.  The game will validate the move and update the board.
5.  If the move is invalid, an error message will be displayed, and the player will be prompted to try again.
6.  The turn then switches to Player 'O', and the process repeats.
7.  The game ends when a player gets three of their marks in a row, column, or diagonal, or when all spaces on the board are filled, resulting in a draw.
