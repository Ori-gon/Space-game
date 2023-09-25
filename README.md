# Space Game

This is a space game where the player controls a gun to shoot down aliens. The game is written in Python using the Pygame library.

### Code Structure

The code is organized into the following files:

* `bullet.py`: defines the `Bullet` class
* `controls.py`: defines the `events`, `update`, `update_bullets`, `gun_kill`, `update_inos`, and `inos_check` functions
* `gun.py`: defines the `Gun` class
* `highscore.txt`: stores the high score
* `ino.py`: defines the `Ino` class
* `scores.py`: defines the `Scores` class
* `space_game.py`: the main game file
* `stats.py`: defines the `Stats` class

### How to Play

To play the game, run `space_game.py`. Use the arrow keys to move the gun left and right, and press the spacebar to shoot bullets. The goal is to shoot down all of the aliens before they reach the bottom of the screen.

### Code Explanation

The following is a step-by-step explanation of the code:

1. The `bullet.py` file defines the `Bullet` class. The `Bullet` class has the following attributes:

    * `screen`: the screen that the bullet will be drawn on
    * `rect`: the rectangle that represents the bullet
    * `color`: the color of the bullet
    * `speed`: the speed of the bullet
    * `x`: the x-coordinate of the bullet
    * `y`: the y-coordinate of the bullet

2. The `controls.py` file defines the following functions:

    * `events`: handles the events that occur in the game
    * `update`: updates the game state
    * `update_bullets`: updates the position of the bullets
    * `gun_kill`: handles the collision between the gun and the aliens
    * `update_inos`: updates the position of the aliens
    * `inos_check`: checks if any of the aliens have reached the bottom of the screen

3. The `gun.py` file defines the `Gun` class. The `Gun` class has the following attributes:

    * `screen`: the screen that the gun will be drawn on
    * `image`: the image of
