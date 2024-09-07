# Snake Game - Built with Phaser.js

This project is a classic Snake Game implemented using the Phaser 3 game framework. The game features smooth snake movement, dynamic food generation, scoring, and game-over conditions. Players control the snake using arrow keys and the objective is to grow the snake as long as possible by eating food while avoiding collisions with itself or the walls.

## Features

- **Smooth Movement**: The snake moves in a grid-based system, ensuring that movement is consistent and fluid.
- **Food Collection**: Food spawns randomly on the grid, and every time the snake eats a piece of food, it grows longer and the player's score increases.
- **Collision Detection**: The game detects collisions between the snake and its own body, ending the game when a collision occurs.
- **Dynamic Difficulty**: As the snake grows longer, the game becomes progressively more challenging, requiring faster reactions from the player.
- **Responsive UI**: The game features a score display and a game-over screen, allowing the player to restart the game or quit.
- **Sound Effects and Music**: Enjoy sound effects for eating food, game over, and background music that enhances the gameplay experience.

## Technologies Used

- **Phaser 3**: A powerful 2D game framework used for game creation.
- **JavaScript (ES6)**: The core language used to develop the game logic.
- **HTML5 and CSS3**: Used for the game's user interface and layout.
- **Assets**: Custom sprites for the snake and food, along with sound effects for added immersion.

## How to Play

1. Use the arrow keys to control the snake's direction:
   - **Left Arrow** - Move left
   - **Right Arrow** - Move right
   - **Up Arrow** - Move up
   - **Down Arrow** - Move down
2. The goal is to eat the food that randomly appears on the screen.
3. Every time the snake eats, it grows longer, and your score increases by 10 points.
4. The game ends when the snake collides with itself or the walls.
5. After the game ends, a "Game Over" screen will appear, allowing you to restart the game.

## Game Controls

- **Arrow Keys**: Control the snake's movement.
- **Restart Button**: Restart the game after a game over.
- **Quit Button**: Quit the game at any time.

## Setup Instructions

To run this game locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/snake-game-phaser.git

   
Future Enhancements
Add levels with increasing difficulty.
Implement power-ups and obstacles.
Add mobile support and touch controls.
Credits
Phaser.js: Phaser 3 game framework.
Snake and Food Sprites: Custom game assets.
Sound Effects: Various sound effects used for in-game actions.
