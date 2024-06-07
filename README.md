# SnakeGame

This is a simple Snake game implemented in Python using the Turtle module. The game features a snake that grows longer as it eats food and ends if it collides with walls or itself.

## Table of Contents

- [Files](#files)
- [How to Play](#how-to-play)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [License](#license)

## Files

1. **main.py**: Contains the main game loop and initializes the game window. It creates instances of the Snake, Food, and Scoreboard classes and controls the game flow.

2. **scoreboard.py**: Defines the Scoreboard class responsible for tracking the player's score and high score. It updates the scoreboard display and manages high score persistence.

3. **snake.py**: Defines the Snake class representing the snake in the game. It handles snake movement, growth, collision detection, and direction control.

4. **food.py**: Defines the Food class responsible for generating food items for the snake to eat. It randomly positions food on the screen when eaten by the snake.

## How to Play

- Use the arrow keys (Up, Down, Left, Right) to control the snake's movement.
- The snake grows longer each time it eats food.
- Avoid collisions with walls or the snake's own tail to prevent game over.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/snake-game.git
