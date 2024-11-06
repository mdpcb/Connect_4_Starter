# Connect 4 Game Assignment

## Objective
Create a console-based **Connect 4** game in Java. The game should allow two players to take turns dropping pieces into a 7x6 grid, aiming to get four in a row horizontally, vertically, or diagonally.

## Requirements

1. **Grid Setup**:
   - Create a 7x6 grid using a 2D array.
   - Represent empty cells with `.` or `-`.
   - Player 1's pieces should be represented by `X`, and Player 2's pieces by `O`.

2. **Game Mechanics**:
   - Players take turns choosing a column (0-6) to drop their piece into.
   - Each piece falls to the lowest available row in the chosen column.
   - The game should detect when a player wins by getting four pieces in a row horizontally, vertically, or diagonally.
   - If the grid fills up with no winner, the game should end in a draw.

3. **Basic Display**:
   - Display the grid after each turn, updating it to show newly placed pieces.
   - Print player instructions and prompt for column selection each turn.
   - Display a message indicating a win or draw when the game ends.

## Extra Credit
- **Computer Player**: Add an option for Player 2 to be controlled by a simple computer AI that makes random or strategic moves.

## Example of Basic Gameplay

```plaintext
Connect 4 Board:
    0 1 2 3 4 5 6
0   . . . . . . .
1   . . . . . . .
2   . . . . . . .
3   . . . . . . .
4   . . . . . . .
5   . . . . . . .

Player 1, enter a column (0-6): 3

Connect 4 Board:
    0 1 2 3 4 5 6
0   . . . . . . .
1   . . . . . . .
2   . . . . . . .
3   . . . . . . .
4   . . . . . . .
5   . . . X . . .

Player 2, enter a column (0-6): 
```
