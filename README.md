# Snake Game

A classic Snake game built in Python using the Turtle graphics library.

## What it does

- Classic Snake gameplay: control the snake with the arrow keys, eat food to grow, and avoid hitting the walls or your own tail
- Tracks your current score and persists the high score between games
- Resets the game automatically on collision, ready to play again

## How it works

- **`main.py`** — sets up the game window, handles key bindings, and runs the main game loop, including collision detection
- **`snake.py`** — defines the `Snake` class, managing the snake's segments, movement, growth, and direction changes
- **`food.py`** — defines the `Food` class, placing food at random positions on the screen
- **`scoreboard.py`** — defines the `Scoreboard` class, tracking and displaying the current score, and reading/writing the high score to `data.txt`
- **`data.txt`** — stores the persisted high score between sessions

## Tech used

- Python 3
- Turtle graphics library
- Object-oriented design (separate classes for the snake, food, and scoreboard)
- Event-driven programming (key press listeners drive the snake's movement)

## What I'd improve next

- Add increasing difficulty (speed) as the score goes up
- Add a pause/restart option without needing to close the window
- Prevent the snake from being able to instantly reverse into itself

## Background

Built as part of a 100 Days of Code Python bootcamp, while working toward a software engineering internship.
