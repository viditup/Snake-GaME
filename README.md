# Snake Game

A simple and engaging snake game developed using Java with a graphical user interface (GUI). The game features smooth animations, interactive gameplay, and a score-tracking system. This project is a fun implementation of the classic Snake game using Java Swing components.

## Screenshots


*Start Screen of Snake Game*


*Gameplay in Progress*

  
*Game Over Screen*

## Project Overview

This project replicates the classic Snake game where the player controls the snake, aiming to eat food (represented by enemies), which causes the snake to grow longer. The game continues until the snake collides with itself. The project is developed using Java with a graphical user interface (GUI) implemented using Swing components.

The snake moves in four directions: up, down, left, and right. The game keeps track of the snake's length, score, and provides a "Game Over" screen once the snake collides with itself.

## Features

- **Snake Movement**: Control the snake using the arrow keys.
- **Score Tracking**: The game tracks and displays the player's score based on the length of the snake.
- **Dynamic Enemy Generation**: Enemies are randomly placed on the screen as food for the snake.
- **Smooth Animations**: The snake moves smoothly with keypress events, and game elements are drawn using Java's `Graphics` class.
- **Game Over Screen**: The game displays a "Game Over" message and provides an option to restart the game by pressing the spacebar.

## Technologies Used

- **Java**: Core programming language used to implement the game logic and graphical interface.
- **Swing**: A Java library for building graphical user interfaces (GUIs).
- **Java AWT**: For handling events and graphics.
- **Random**: Used for generating random positions of enemies.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/snake-game.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd snake-game
   ```

3. **Compile and Run the Game**:
   
   - If you are using an IDE like IntelliJ IDEA or Eclipse, simply open the project and run the `Main.java` file.
   - Alternatively, use the following commands in the terminal:

     ```bash
     javac Main.java Gameplay.java
     java Main
     ```

4. The game window will open, and you can start playing.

## How to Play

- **Move the Snake**: Use the arrow keys (Right, Left, Up, Down) to navigate the snake.
- **Eat Enemies**: The snake grows in length every time it eats an enemy (represented by a small icon).
- **Avoid Collisions**: The game ends if the snake collides with itself.
- **Restart the Game**: Press the spacebar to restart the game after a game-over.

## Game Controls

- **Arrow Keys**: Control the snake’s movement (Up, Down, Left, Right).
- **Spacebar**: Restart the game after a game-over.

## Example Gameplay

- Upon starting the game, you will see the snake initially at a small size.
- As the snake eats the food (enemies), its length increases, and the score gets updated.
- If the snake collides with its own body, the game ends and shows a "Game Over" screen.
- Press space to restart and try to beat your high score.

## Contributing

Feel free to fork this project, submit issues, or make pull requests. If you'd like to contribute, please ensure that any contributions follow the guidelines below:

- Write clean and maintainable code.
- Follow Java coding conventions.
- Ensure that your code works and passes any unit tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
