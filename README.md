# Snake-Game-Using-Python
# Snake Game

A classic Snake game implementation in Python using Pygame by ADITYA.

## Description

This is a traditional Snake game where the player controls a red snake to eat green food blocks. The snake grows longer with each food consumed, and the game speed increases progressively. The objective is to achieve the highest score possible while avoiding collisions with walls and the snake's own body.

## Features

- Classic snake gameplay mechanics
- Real-time score display
- Progressive speed increase
- Game over screen with restart option
- Smooth snake movement with arrow key controls

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Ensure Python 3.x is installed on your system
2. Install Pygame using pip:
   ```bash
   pip install pygame
   ```

## How to Run

1. Save the code as `snake_game.py`
2. Navigate to the file directory in terminal/command prompt
3. Execute the game:
   ```bash
   python snake_game.py
   ```

## Game Controls

### During Gameplay:
- **Left Arrow (←)**: Move snake left
- **Right Arrow (→)**: Move snake right  
- **Up Arrow (↑)**: Move snake up
- **Down Arrow (↓)**: Move snake down

### Game Over Screen:
- **Q**: Quit the game
- **C**: Continue/Play again

## Game Rules

1. Control the red snake using arrow keys
2. Eat green food blocks to grow and increase score
3. Avoid hitting the screen boundaries
4. Avoid colliding with the snake's own body
5. Game speed increases as you collect more food

## Game Configuration

The following parameters can be modified in the code:

```python
width = 600           # Screen width
height = 400          # Screen height  
block_size = 10       # Size of snake segments and food
snake_speed = 7       # Initial game speed
```

## Color Scheme

- **Background**: Black (0, 0, 0)
- **Snake**: Red (255, 0, 0) 
- **Food**: Green (0, 255, 0)
- **Text**: White (255, 255, 255)

## Technical Implementation

- **Game Loop**: Main game logic with event handling
- **Collision Detection**: Boundary and self-collision checking
- **Food Generation**: Random food placement using coordinate rounding
- **Score System**: Based on snake length minus initial length
- **Speed Progression**: Incremental speed increase with each food consumed

## File Structure

```
snake_game.py         # Main game executable
```

## Functions Overview

- `score_display(score)`: Renders and displays current score
- `draw_snake(snake_block, snake_list)`: Draws snake segments on screen
- `game_loop()`: Main game logic and event handling

## Author

S MOKSH ADITYA

## Version

Current version includes basic Snake game functionality with score tracking and speed progression.

---

**Enjoy the classic Snake gaming experience!** 🐍
