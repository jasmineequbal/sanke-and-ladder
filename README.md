# Snake and Ladder Game

## Description

This is a simple Java-based Snake and Ladder game for two players. The game simulates rolling a dice and moves the players accordingly. It also implements snakes and ladders, which either advance or reduce the player's position on the board.

## How to Play

- Two players start at position `0`.
- Each player takes turns rolling a dice (random number between 1 and 6).
- If a player lands on a ladder, they move up to a higher position.
- If a player lands on a snake, they move down to a lower position.
- The first player to reach exactly `100` wins.

## Features

- Random dice rolling.
- Ladders that move players up.
- Snakes that move players down.
- Two-player gameplay.

## Code Structure

- `main()` initializes the game and calls `startgame()`.
- `startgame(int player1, int player2)`: Runs the game loop until a player reaches 100.
- `rolladice()`: Generates a random number between 1 and 6.
- `checkLadderOrSnake(int p)`: Checks if a player has landed on a snake or ladder and updates the position.

## How to Run the Program

1. Install Java on your system.
2. Copy the `snakeladdergame.java` file to a directory.
3. Open a terminal or command prompt.
4. Compile the code using:
   ```bash
   javac snakeladdergame.java
   ```
5. Run the game using:
   ```bash
   java snakeladdergame
   ```

## Example Output

```
Player 1 rolled a 4
Player 1 moved to 4
Player 2 rolled a 5
Player 2 moved to 5
...
Player 1 reached 100! Player 1 wins!
```

## Improvements to Consider

- Add user input for player names.
- Implement a GUI for a better experience.
- Display a proper board visualization.

## Author

Jasmine Eqbal

## License

This project is licensed under the MIT License.
