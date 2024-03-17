# Tic Tac Toe Game using Java Swing

This project is a simple implementation of the classic Tic Tac Toe game using Java Swing for the graphical user interface. In this version of the game, the player turn is determined randomly. Screenshots of the game interface are attached below.

## Screenshots
-player X got the first turn
![X Turn Screenshot](https://github.com/SubediBinod/JavaSwingPractice/assets/105643264/f809d6ff-0bdb-4c0f-835d-04a23c1493f6)



-player O got the first turn
![oturn](https://github.com/SubediBinod/JavaSwingPractice/assets/105643264/3981a5f5-8b84-45be-95b8-5ed7c0235085)


-Player X wins ::
![xwins](https://github.com/SubediBinod/JavaSwingPractice/assets/105643264/a5388c68-5220-4340-857d-82420642b906)



-Player O wins ::
![owins](https://github.com/SubediBinod/JavaSwingPractice/assets/105643264/eb847869-29da-48c0-a7b9-669bbfb0092c)


-Game draws::
![draw](https://github.com/SubediBinod/JavaSwingPractice/assets/105643264/10e27e28-16c6-4fae-9f2a-30ac96271ae7)


## How to Play

1. **Starting the Game**: Run the Java application to launch the Tic Tac Toe game interface.
   
2. **Game Interface**:
   - The game interface consists of a 3x3 grid representing the Tic Tac Toe board.
   - Each cell of the grid is a button where players can make their moves.

3. **Gameplay**:
   - Players take turns clicking on the cells to make their moves.
   - The game alternates between two players, "X" and "O", with the player turn determined randomly at the start of each game.

4. **Winning Condition**:
   - The game ends when one player successfully places three of their marks (either "X" or "O") in a row, column, or diagonal.
   - The player who achieves this first is declared the winner.

5. **Restarting the Game**:
   - After the game ends (either due to a win or a draw), players have the option to restart the game to play again.

## Implementation Details

- **GUI Components**: The game interface is built using Java Swing components such as `JFrame`, `JPanel`, and `JButton`.
- **Game Logic**: The game logic is implemented to handle player moves, determine the winner, and manage the game state.
- **Random Player Turn**: The player turn is determined randomly at the start of each game using the `java.util.Random` class.

## Requirements

- Java Development Kit (JDK) installed on your system.
- An integrated development environment (IDE) such as Eclipse, IntelliJ IDEA, or NetBeans for running the Java application.

## Getting Started

1. Clone the repository to your local machine.
2. Open the project in your preferred IDE.
3. Compile and run the `Main.java` file to start the game.




