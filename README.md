# windstream_runner


This code appears is a Python script for a simple game using the Pygame library. The game features a character (likely Sonic the Hedgehog) that can jump over or avoid obstacles while collecting items. Here is a brief description of the key components and functionalities of the code:

1. Imports: The code imports various modules, including `pygame` for game development, and custom modules such as `enemy`, `high_scores_screen`, `register`, `variables`, and functions from `functions`. These modules are likely used for defining game elements and functions.

2. Main Game Loop: The game operates within a `while PLAYING` loop. The game continues to run as long as the `PLAYING` variable is set to `True`.

3. User Input: The code handles user input, such as key presses and mouse clicks, to control the game. For example, the spacebar allows the character to jump.

4. Obstacle and Item Spawning: The code manages the spawning of obstacles and items in the game world. It determines when and where enemies and items (hearts) appear, controlling their movement and interaction with the player character.

5. Scoring: The code keeps track of the player's score based on how long they have survived in the game. It also handles high score recording and the display of both the current and best scores.

6. Game Over: When the player's character loses all of their health, the game enters a "Game Over" state. During this state, the player is shown their last score, the best score, and given the option to restart the game.

7. Graphics: The code manages the display of game elements, including character animations (running and jumping), obstacles, and the game's background. It also handles visual effects for damage and healing.

8. Sound: The code incorporates sound effects, such as jumping and collision sounds, to enhance the gaming experience.

Overall, the main game is a 2D platformer-style game. It includes features like character movement, obstacle avoidance, scoring, and game over conditions. 
