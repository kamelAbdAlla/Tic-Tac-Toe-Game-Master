# Tic-Tac-Toe-Game-Master
This code is an implementation of the classic Tic Tac Toe game using the Python programming language and the OpenCV library for creating a graphical user interface (GUI). The game can be played by two human players or a human player against the computer. The computer player uses the Minimax algorithm to decide its next move, making it a challenging opponent.

The GUI displays a 3x3 grid where the players can place their marks. The game keeps track of whose turn it is, whether the game has been won, and if there is a draw. The GUI also allows the user to reset the game and exit the program.

The game logic is implemented using classes and functions. The Block class represents a single cell in the Tic Tac Toe grid, while the GUI class represents the GUI and game logic of Tic Tac Toe. The GUI class has methods for resetting the game, drawing the GUI and game screen, handling mouse clicks, and deciding the next move for the computer player.

The mainLoop method is the main game loop that runs until the user closes the window. The loop displays the current state of the game and checks for user input. If the user clicks on a cell, the setBlockInPos method is called to update the state of the game. If the computer player's turn comes up, the nextMove method is called to decide the next move.

The nextMove method uses the Minimax algorithm to decide the next move. The algorithm recursively explores all possible moves and evaluates the score of each move. The algorithm then chooses the move with the highest score.

