Simple Pong Game
This is a simple implementation of the classic game Pong using the SDL2 library in C. The game features a bouncing ball, a paddle controlled by the player, and basic collision detection.

Table of Contents
Prerequisites
Build
How to Play
Controls
Game Rules
Customization
Acknowledgments
Prerequisites
Before you can run the game, you need to have the SDL2 library installed. You can install it on most Linux distributions using the following command:

sudo apt-get install libsdl2-dev
Build
You can build the game by using the provided Makefile. Open your terminal and navigate to the game directory, then run:

make
This will compile the source code and create an executable named game.

How to Play
To start the game, simply run the following command in your terminal:

./game
The game window will appear, and you can begin playing.

Controls
Use the left arrow key to move the paddle left.
Use the right arrow key to move the paddle right.
Press Escape to quit the game at any time.
Game Rules
The objective of the game is to bounce the ball off the paddle and prevent it from touching the bottom of the screen.
Each time you successfully bounce the ball off the paddle, your score will increase.
The game gets progressively faster as you score more points.
If the ball touches the bottom of the screen, the game will reset, and your score will be reset to zero.
Customization
You can customize various aspects of the game by modifying the source code. For example:

Adjust the initial position and velocity of the ball and paddle in the setup function.
Change the colors of the ball and paddle by modifying the SDL_SetRenderDrawColor calls in the render function.
Customize the game window size and frame rate by modifying the constants defined in constants.h.
Feel free to explore the source code and make changes to create your unique version of the game.

Acknowledgments
This game is a simple example of game development using the SDL2 library in C. It was created for educational purposes and as a starting point for building more complex games. You can use this code as a foundation for creating your own games and exploring the world of game development.

Enjoy playing Pong!
