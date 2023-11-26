## Snake Module

### Description
The `Snake` module defines the `Snake` class, which represents the snake entity in the Snake Game. This class utilizes the Turtle graphics library to manage the snake's appearance, movement, and growth throughout the game.

### Constants
- `STARTING_POSITIONS`: A list of tuples representing the initial coordinates of the snake's segments.
- `MOVE_DISTANCE`: The distance the snake moves in each step.
- Constants (`UP`, `DOWN`, `LEFT`, `RIGHT`) representing the directions the snake can move.

### Functionality

#### 1. Initialization
   - The `__init__` method initializes the snake's properties.
   - It creates the initial snake with three segments using the `create_snake` method.
   - The snake's head is set to the first segment in the list.

#### 2. Creating the Snake
   - The `create_snake` method populates the `segments` list with three turtle segments.
   - Each segment is added using the `add_segment` method.

#### 3. Adding a Segment
   - The `add_segment` method creates a new turtle segment, sets its color and position, and appends it to the `segments` list.

#### 4. Extending the Snake
   - The `extend` method adds a new segment to the snake, positioned at the last segment's location.

#### 5. Moving the Snake
   - The `move` method updates the position of each snake segment to follow the one in front.
   - The head is moved forward by the `MOVE_DISTANCE` in its current direction.

#### 6. Changing Direction
   - Methods (`up`, `down`, `left`, `right`) allow the snake to change its direction but prevent it from reversing into itself.

### Usage
1. Import the `Snake` class from the `snake.py` module in the main game script.
   ```python
   from snake import Snake
   ```

2. Create an instance of the `Snake` class.
   ```python
   snake = Snake()
   ```

3. Use the provided methods to control the snake's movement and direction.

### Example
```python
# Import Snake class
from snake import Snake

# Create Snake instance
snake = Snake()

# Move the snake up
snake.up()

# Extend the snake
snake.extend()

# Move the snake forward
snake.move()
```

### Note
- This module encapsulates the behavior of the snake, providing methods for its creation, movement, and interaction with the game.
