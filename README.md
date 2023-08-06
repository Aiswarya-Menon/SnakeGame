# Snake Game
Snake Pygame is a 2D arcade game built using the Python programming language and Pygame, a set of Python modules designed for writing video games. The goal of the game is to guide a 'snake' towards food items that appear randomly in the game area. With each piece of food consumed, the snake increases in length. The game becomes progressively difficult as the snake grows longer, as the player must avoid colliding with the snake's own body. The player also needs to prevent the snake from touching the boundaries of the game area. The game utilizes simple yet engaging graphics and controls, providing a nostalgic and enjoyable gaming experience.

# Team Members
1) Aiswarya Menon K    ->  Aiswarya-Menon
1) Abheda K P          ->  Abheda-kp

# Team Name - Slytherin

# Link To Video - 
https://drive.google.com/drive/folders/1q60dbtJYSuCqdZ1k5dpYM2oKyMSQ2-g6?usp=drive_link

# How the tool works
Initialization: The program initializes the Pygame mixer and Pygame itself. It sets up some color constants, loads in some image files to use as backgrounds, creates a game window with Pygame, sets the title of the game window, and sets up the background music to play in a loop.

Variables: The program defines some variables like clock and font. These will be used for timing and rendering text in the game, respectively.

Functions:

text_screen: It is used to draw text on the screen at a specific location.
plot_snake: It is used to draw the snake in the game window. The snake is a collection of rectangles, where each rectangle is a segment of the snake's body.
welcome: This function sets up the welcome screen that waits for the player to press the return key to start the game.
gameloop: This function contains the main game loop, where all the magic happens. It processes events (like player input), updates the game state, and renders the new game state on the screen.
Game Logic:

At the beginning of the game, the snake starts with a length of one at a predefined location. The game also randomly places food somewhere in the game area.
If the snake eats the food (i.e., the snake's head position coincides with the food's position), then the score increases by 10, a new food item is placed randomly within the game area, and the snake's length increases.
The player can control the direction of the snake's movement. The snake continuously moves in the last chosen direction. If the snake's head hits its body or it goes out of bounds, it's game over.
The score and high score are displayed in the game window during gameplay. If the current score exceeds the high score, the high score is updated.
When the game is over, the score is saved as the high score if it's greater than the previous high score, and a game-over screen is displayed. The player can start a new game by pressing the return key.
Execution: The game starts by calling the welcome function, which then enters into the gameloop function as soon as the player presses the return key, starting the actual game.

# Libraries Used
1) pygame
2) random
3) os

# How to configure and Run
First, install the latest version of Python on your computer. You can download it from the official Python website.

Next, install the pip package manager. This will allow you to easily install and manage Python packages.

Install the virtualenv package. This will allow you to create isolated Python environments, which can help prevent conflicts between different projects.

Install the Pygame library. This can be done using pip by running the command "pip install pygame" in your command prompt.

Once Pygame is installed, you can test if it's working by creating a new Python file and importing Pygame. If you don't get any errors, then it's installed correctly.

Create a new Python project in your preferred IDE or text editor. It is recommended to use something like PyCharm or Atom.
