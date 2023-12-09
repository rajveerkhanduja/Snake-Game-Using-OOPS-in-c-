# Snake-Game-Using-OOPS-in-c-
Snake Game Using OOPS in c++

OBJECTIVES:

By implementing this:

	One can expand his/her knowledge in the hypothesis of data structures.
	To successfully implement Dijkstra’s Algorithm.¬¬¬¬¬
	Optimize the code for efficiency, especially when dealing with large graphs.
	Implement error-handling mechanisms to gracefully handle unexpected situations, such as invalid input or other runtime errors.


INTRODUCTION:

The given program is a console-based Snake game implemented in C++. The game involves controlling a snake on the screen and trying to eat food to grow longer. The objective is to achieve the highest score possible without colliding with the snake's own body or the boundaries of the screen. The user is asked for the difficulty level and based on that, Snake’s Speed is set.


KEY CONCEPTS:

HEADER FILES USED :-

•	iostream :- This header file is used for input/output operations.

•	conio.h:- This header file provides functions for console input/output operations.

•	stdexcept :- This header file defines the standard exceptions.

•	windows.h :- This header file is used for Windows-specific functions, such as setting the console cursor position.

•	ctime :- This header file is used for generating random numbers based on the current time.


OOPS CONCEPTS USED :-

•	Encapsulation :- The program encapsulates related data and functions within classes. For example, the Snake class encapsulates the snake's length, direction, and body, as well as the functions to change the direction and move the snake.

•	Abstraction :- The program abstracts the game logic and user interface into separate classes. The Board class abstracts the game board and handles the game logic, while the Snake class abstracts the snake and its movement.

•	Inheritance :- The program does not explicitly demonstrate inheritance as it does not define any derived classes. However, the use of classes and objects follows the principles of inheritance, as objects of the Snake class are created within the Board class.

•	Polymorphism :- The program does not explicitly demonstrate polymorphism as it does not define any virtual functions or use dynamic binding. However, the use of classes and objects allows for polymorphic behavior, as different objects can have different states and behaviors.



CODE STRUCTURE:


GLOBAL CONSTANTS AND VARIABLES USED :-

•	MAX_LENGTH :- This constant defines the maximum length of the snake.

•	DIR_UP, DIR_DOWN, DIR_LEFT, DIR_RIGHT :- These constants represent the directions in which the snake can move.

•	consoleWidth, consoleHeight :- These variables store the width and height of the console window.


STRUCTURES AND CLASSES USED :-

•	Point structure :- This structure represents a point on the screen with x and y coordinates.

•	Snake class:- This class represents the snake in the game. It has member variables for the snake's length, direction, and an array of points representing the snake's body. It also has member functions to change the direction of the snake and move it on the screen.

•	Board class :- This class represents the game board. It has member variables for the snake, food, score, snake speed, and difficulty level. It also has member functions to initialize the game, spawn food, display the current score, draw the game board on the console, update the game state, get user input, and check if the game is won.


FUNCTIONS :-

•	initScreen():- This function initializes the console screen by getting the screen buffer information and setting the console width and height.

•	setCursorPosition(int x, int y):- This function sets the console cursor position to the specified x and y coordinates.

•	main() :- This is the main function of the program. It initializes the game board, enters a game loop, and handles user input and game updates. It also displays the game over or game won message based on the game outcome.


ALGORITHM:

	Step 1: Include necessary headers like <iostream>, <conio.h>,<stdexcept>, <windows.h>, <ctime> and  <limits>.

	Step 2: Define constants MAX_LENGTH and direction constants  DIR_UP, DIR_DOWN, DIR_LEFT, DIR_RIGHT.

	Step 3: Create initScreen() function to initialize the screen dimensions using GetStdHandle and CONSOLE_SCREEN_BUFFER_INFO.

	Step 4: Define Point structure with xCoord and yCoord.

	Step 5: Create Snake class with length, direction, and an array of Point for the snake body. Implement methods for getting length, changing direction, moving, and collision checks.
	Step 6: Create Board class with a snake, speed, score, and methods for spawning food, displaying score, drawing board, updating game state, and getting user input. Determine snake speed based on difficulty level.
	Step 7: In main() Seed random, create Board object, enter game loop.
	Step 8: After exiting the loop, check if the game was won or lost. Print "Game Won" or "Game Over" accordingly.
	Step 9: Delete the dynamically allocated Board object for memory cleanup.
	Step 10: Implement error handling for memory allocation and other potential issues.

PROBLEMS FACED:

The problems faced during the implementation of the Snake Game using OOPS with C++ are:
	The code for implementing and understanding the program is a bit complicated and time taking process.
	Confused in the logic part of the class Board() where we implemented the movement of snake, spawning the food, and position at which the food had to be placed randomly.
	There were many syntax, runtime and logical errors during the execution, allocation, and deallocation of memory dynamically.

CONCLUSION:

In conclusion, the Snake game implemented in C++ is a functional and playable game. It allows the player to control a snake, eat food, and increase their score. The code snippet provided demonstrates the basic functionality of the game, but there is room for improvement in terms of error handling, code organization, and user input validation. Overall, the Snake game serves as a good starting point for further development and customization.

THE END
