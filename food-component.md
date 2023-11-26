## Food Module

### Description
The `Food` module defines the `Food` class, which represents the food items in the Snake Game. Each time the snake consumes food, a new food item is randomly placed on the screen. This class inherits from the `Turtle` class in the Turtle graphics library.

### Functionality

#### 1. Initialization
   - The `__init__` method sets up the initial properties of the food.
   - The food is represented by a blue circular shape.
   - It is positioned using Cartesian coordinates and has a reduced size compared to the default turtle shape.

#### 2. Refreshing Food
   - The `refresh` method is responsible for repositioning the food on the screen after it has been eaten by the snake.
   - Random coordinates within the game window boundaries (-280 to 280) are generated for the new food position.
   - The `goto` method is used to move the food to the newly generated coordinates.

### Usage
1. Import the `Food` class from the `food.py` module in the main game script.
   ```python
   from food import Food
   ```

2. Create an instance of the `Food` class.
   ```python
   food = Food()
   ```

3. The `refresh` method can be called to reposition the food when it is consumed by the snake.

### Example
```python
# Import Food class
from food import Food

# Create Food instance
food = Food()

# Call refresh to reposition the food
food.refresh()
```

### Note
- This module encapsulates the logic related to the creation and positioning of food items, contributing to the overall functionality of the Snake Game.
