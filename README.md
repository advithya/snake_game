# Snake Game by Advithiya V

This is a classic Snake Game implemented using Python and Pygame. The objective of the game is to control the snake to eat food and grow in length while avoiding collisions with the walls or itself.

## Features
- Classic snake gameplay
- Score display
- Restart option after game over

## Installation

1. **Clone the Repository**:
bash
git clone <repository_url>
cd snake_game


2. **Create a Virtual Environment**:
bash
python -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate


3. **Install Dependencies**:
bash
pip install pygame


## How to Run

1. Navigate to the project directory:

bash
cd snake_game


2. Run the game:
bash
python snake_game.py


## How to Play

- Use the arrow keys to control the direction of the snake.
- The objective is to eat the green food blocks to grow in length.
- Avoid colliding with the walls or the snake's own body.
- The game ends when the snake collides with the wall or itself.
- After the game is over, press `C` to play again or `Q` to quit.

## Code Overview

- **`snake_game.py`**: The main game file containing all the game logic and functions.
  - **Colors**: Defined for different game elements.
  - **Display**: Initializes the game window.
  - **Game Loop**: Contains the main game loop where events are handled, and the game state is updated.
  - **Functions**:
    - `Your_score(score)`: Displays the current score.
    - `our_snake(snake_block, snake_list)`: Draws the snake on the screen.
    - `message(msg, color)`: Displays messages on the screen.
    - `gameLoop()`: The main function that runs the game loop.

## Dependencies

- Python 3.x
- Pygame

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Pygame library for making game development in Python easier.
