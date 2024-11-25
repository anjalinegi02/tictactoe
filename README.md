# tictactoe
This project is a graphical implementation of the classic Tic Tac Toe game, built using Python's tkinter library. It provides a user-friendly interface and supports two modes of play: Single Player (against a computer) and Multiplayer (two players take turns). The game is designed to be engaging and educational, showcasing fundamental programming concepts like event handling, game logic, and artificial intelligence.

Key Features:

Game Modes:
Single Player: Compete against a computer opponent powered by the minimax algorithm, ensuring challenging gameplay.
Multiplayer: Two players can play locally, alternating turns.

Graphical User Interface (GUI):
The game board is a 3x3 grid of buttons.
Dynamic labels display the game status (e.g., player turns, win, or draw outcomes).
Mode selection buttons allow easy switching between single-player and multiplayer modes.
A "Restart Game" button resets the game for a new match.

Win and Draw Detection:
The program detects win conditions across rows, columns, and diagonals.
It declares a draw if all spaces are filled without a winner.

AI Implementation:
The computer opponent (O) uses the minimax algorithm, ensuring it makes the best possible moves.
The AI evaluates potential game states to maximize its chances of winning or minimize losses.

Responsive Design:
Buttons and labels dynamically update based on player interactions.
Visual cues like button colors and status messages enhance the user experience.
