# Snake Game
This is a simple Snake Game implemented in Python using the Turtle graphics library. The game features a snake that moves around the screen, eating food to grow longer. The objective is to survive as long as possible without colliding with the snake's own body or the screen boundaries.

## How to Play
### Controls:
- Use the arrow keys (Up, Right, Down, Left) to change the snake's direction.
### Game Rules:
- The snake starts with a length of 5 segments.
- Each time the snake eats food, it grows longer.
- The game ends if the snake collides with itself or reaches the screen boundaries.
## Implementation Details
### The game is implemented with the following components:

### Snake Movement:

- The snake moves based on a timer-controlled loop.
- The snake's head position is updated according to the chosen direction, and the tail follows.
### Food:

- Red squares represent food.
- The food position changes each time the snake eats it.
### Collision Handling:

- The game checks for collisions with itself and handles screen boundaries appropriately.
### Game Window:

- The game window is set up using the Turtle graphics library.
### Input Handling:

- Event listeners are set up to capture arrow key inputs for changing the snake's direction.
### How to Run
- Ensure you have Python installed on your system.
- Copy the provided code into a Python file (e.g., snake_game.py).
- Run the script using a Python interpreter.
### Run:
- python snake_game.py
