# Stone, Paper, Scissors Game

This is a simple command-line Stone, Paper, Scissors game implemented in C++. The game allows the user to play against the computer. The game logic randomly selects between "Stone," "Paper," or "Scissors" for the computer, and the user inputs their choice. The program then determines the winner based on the rules of the game.

## Game Rules
- **Stone (s)** beats **Scissors (z)**.
- **Scissors (z)** beat **Paper (p)**.
- **Paper (p)** beats **Stone (s)**.
- If both the user and the computer make the same choice, the game is a draw.

## How to Play
1. Clone this repository to your local machine.
2. Compile the C++ code using a C++ compiler.
3. Run the compiled program.
4. When prompted, enter your choice:
   - `s` for Stone
   - `p` for Paper
   - `z` for Scissors
5. The computer will randomly choose its option, and the result of the game will be displayed.

## Code Explanation
The code consists of two main parts:
1. **`game()` Function**: Determines the outcome based on the user and computer's choices. Returns:
   - `-1` for a draw.
   - `1` if the user wins.
   - `0` if the computer wins.

2. **`main()` Function**: Handles the game's flow:
   - Generates a random choice for the computer.
   - Prompts the user to enter their choice.
   - Calls the `game()` function to decide the winner.
   - Displays the result.

## Compilation and Execution
To compile and run the program, use the following commands:

```bash
g++ -o stone_paper_scissors game.cpp
./stone_paper_scissors
