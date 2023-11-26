Components
1. Screen Setup
The game window is set up with a black background, dimensions of 600x600 pixels, and titled "My Snake Game."
Turtle graphics are used to draw and update the game elements.
2. Snake Initialization
The snake is initialized using the Snake class from the snake.py module.
Arrow keys are configured to control the snake's movement.
3. Food Generation
The Food class from the food.py module is used to create and refresh food items on the screen.
4. Scoreboard
The Scoreboard class from the scoreboard.py module keeps track of the player's score and displays it on the screen.
5. Game Loop
The game runs in a loop (while game_is_on), updating the screen, moving the snake, and checking for collisions.
The snake can eat food, leading to score increments, and collisions with walls or its own tail result in game over.
6. Controls
Arrow keys (Up, Down, Left, Right) are assigned to control the snake's direction.
