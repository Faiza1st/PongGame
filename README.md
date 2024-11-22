# PongGame
This is a simple implementation of the classic Pong Game using Python and the pygame library. Players control paddles on either side of the screen, trying to bounce the ball past their opponent. The game ends when one player scores a point.

## Features
- Player vs. Player: Two players control paddles on opposite sides of the screen.
- Ball Movement: The ball bounces off the paddles and walls.
- Scoring System: Each player earns a point when the opponent fails to hit the ball.
- Game Over: The game continues until a player reaches a predefined score (default is 5).
- Controls: Each player can move their paddle up and down.

### Game Controls
- Player 1 (Left Paddle):
-- W: Move up
-- S: Move down
- Player 2 (Right Paddle):
-- Up Arrow: Move up
-- Down Arrow: Move down
  
### Scoring
- Each player scores a point when the ball crosses the opponent’s side of the screen.
- The game resets the ball in the center after each point is scored.
- The first player to reach 5 points wins the game (this can be changed by modifying the code).

## Screenshots
<img width="798" alt="Screen Shot 2024-11-22 at 1 13 43 pm" src="https://github.com/user-attachments/assets/007e61b5-d624-4c59-9a7b-f7be270ca0b7">


## Code Overview
The game is implemented using the pygame library to handle graphics, user input, and game logic. The main components of the game include:
- Game Loop: Handles the ongoing movement of the ball, paddle control, and scoring.
- Ball Class: Defines the ball's movement, speed, and collision detection.
- Paddle Class: Handles the movement and drawing of the paddles.
- Collision Detection: Checks for collisions between the ball and the paddles or walls.
- Scoring System: Tracks the score of both players and displays it on the screen.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
