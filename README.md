
# Tic-Tac-Toe Game (CodeSoft C++ Internship - Task 3)

## Description
This is a simple Tic-Tac-Toe game implemented in C++ as part of the CodeSoft C++ Internship (Task 3). The game is designed for two players who take turns marking spaces in a 3×3 grid with 'X' and 'O'. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game. If all spaces are filled without a winner, the game results in a draw.

## Features
- Two-player game (Player X and Player O)
- Input validation to prevent overwriting moves
- Checks for winning conditions after each move
- Detects draw situations

## How to Run
### Prerequisites
- A C++ compiler (G++ or any other standard compiler)
- A terminal or command prompt

### Compilation and Execution
1. Clone this repository or copy the `CodeSoft_Tic-Tac_Toe_Game.cpp` file.
2. Open a terminal or command prompt and navigate to the project directory.
3. Compile the program using:
   ```sh
   g++ -o CodeSoft_Tic-Tac_Toe_Game CodeSoft_Tic-Tac_Toe_Game.cpp
   ```
4. Run the executable:
   ```sh
   ./CodeSoft_Tic-Tac_Toe_Game
   ```

## How to Play
1. The game starts with Player X.
2. Players take turns entering a number (1-9) corresponding to an available position on the board.
3. The board updates after each valid move.
4. The game announces a winner if a player achieves three marks in a row, column, or diagonal.
5. If all spaces are filled without a winner, the game ends in a draw.
6. The game then terminates.

## Sample Board Representation
```
1 2 3
4 5 6
7 8 9
```
Players enter numbers corresponding to the position where they want to place their mark.

## Code Structure
- `showBoard()`: Displays the current state of the board.
- `move()`: Prompts the player for input and updates the board.
- `win()`: Checks if there is a winning condition.
- `draw()`: Checks if the board is full and the game is a draw.
- `switchPlayer()`: Alternates the turn between Player X and Player O.
- `main()`: The main game loop that runs until a win or draw condition is met.

## Future Enhancements
- Implement an AI opponent for single-player mode.
- Add a graphical user interface (GUI).
- Improve input handling for a better user experience.

## License
This project is open-source and available for use under the MIT License.

## Contact
For any questions or contributions, feel free to reach out or create an issue in the repository.

Happy Coding! 🎮
