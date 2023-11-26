## Scoreboard Module

### Description
The `Scoreboard` module defines the `Scoreboard` class, responsible for tracking and displaying the player's score in the Snake Game. It utilizes the Turtle graphics library to manage the display of the score on the game screen.

### Functionality

#### 1. Initialization
   - The `__init__` method sets up the initial properties of the scoreboard.
   - It initializes the score to zero and configures the appearance of the turtle (color, font, etc.).
   - The turtle is positioned at the top of the screen, initially hidden, and the `update_scoreboard` method is called.

#### 2. Updating Scoreboard
   - The `update_scoreboard` method displays the current score on the screen.
   - It uses the `write` method to print the score in the specified font and alignment.

#### 3. Increasing Score
   - The `increase_score` method increments the score by one, clears the previous score display, and updates the scoreboard with the new score.

#### 4. Game Over
   - The `game_over` method positions the turtle at the center of the screen and writes "GAME OVER" when the game ends.

### Usage
1. Import the `Scoreboard` class from the `scoreboard.py` module in the main game script.
   ```python
   from scoreboard import Scoreboard
   ```

2. Create an instance of the `Scoreboard` class.
   ```python
   scoreboard = Scoreboard()
   ```

3. The `increase_score` method can be called to update the score when the snake consumes food.

4. The `game_over` method can be called to display the "GAME OVER" message when the game concludes.

### Example
```python
# Import Scoreboard class
from scoreboard import Scoreboard

# Create Scoreboard instance
scoreboard = Scoreboard()

# Increase score (example: called when snake consumes food)
scoreboard.increase_score()

# Display "GAME OVER" (example: called when game ends)
scoreboard.game_over()
```

### Note
- This module provides a visual representation of the player's score and game status, enhancing the overall gaming experience.
