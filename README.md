# SnakeGame

This is a simple Snake game implemented in Python using the Turtle module. The game features a snake that grows longer as it eats food and ends if it collides with walls or itself.
The game is designed using OOP principles, with each component of the game encapsulated within its own class. This promotes code organization, reusability, and modularity.

## Table of Contents

- [Files](#files)
- [Code Explanation](#code-explanation)
- [How to Play](#how-to-play)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)


## Files

1. **main.py**: Contains the main game loop and initializes the game window. It creates instances of the Snake, Food, and Scoreboard classes and controls the game flow.

2. **scoreboard.py**: Defines the Scoreboard class responsible for tracking the player's score and high score. It updates the scoreboard display and manages high score persistence.

3. **snake.py**: Defines the Snake class representing the snake in the game. It handles snake movement, growth, collision detection, and direction control.

4. **food.py**: Defines the Food class responsible for generating food items for the snake to eat. It randomly positions food on the screen when eaten by the snake.

# Code Explanation

## main.py

- **Purpose**: Initializes the game window and controls the main game loop.
- **Functionality**:
  - Sets up the game screen using the Turtle module.
  - Creates instances of the Snake, Food, and Scoreboard classes.
  - Listens for keyboard input to control the snake's movement.
  - Manages the main game loop, updating the screen, moving the snake, and detecting collisions.
  - Handles game over conditions such as collisions with food, walls, or the snake's own tail.

## scoreboard.py

- **Purpose**: Manages the scoreboard display and high score persistence.
- **Functionality**:
  - Defines the Scoreboard class responsible for displaying the current score and high score.
  - Reads the high score from a file and updates it when necessary.
  - Resets the score and updates the high score when the game ends.

## snake.py

- **Purpose**: Represents the snake in the game and controls its movement.
- **Functionality**:
  - Defines the Snake class with methods to initialize the snake, move it in different directions, and handle collision detection.
  - Manages the snake's segments and growth when it eats food.
  - Handles snake movement based on user input and updates its position accordingly.

## food.py

- **Purpose**: Generates food items for the snake to eat.
- **Functionality**:
  - Defines the Food class responsible for creating and positioning food items on the screen.
  - Generates food at random positions when eaten by the snake.

## How to Play

- Use the arrow keys (Up, Down, Left, Right) to control the snake's movement.
- The snake grows longer each time it eats food.
- Avoid collisions with walls or the snake's own tail to prevent game over.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/snake-game.git
   ```
2. Navigate to the project directory:
   
    ```bash
      cd snake-game
      ```
3. Run the game:
   ```bash
      python main.py
      ```
## Dependencies

Python 3.x

Turtle module

