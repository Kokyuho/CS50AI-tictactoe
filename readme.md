# CS50’s Introduction to Artificial Intelligence with Python
# Project 0: Search: Tic-Tac-Toe

**Aim**: Using Minimax, implement an AI to play Tic-Tac-Toe optimally.

Description: In this problem set, a type of adversarial search algorithm called Minimax is implemented to play the game Tic-Tac-Toe. Minimax represents winning conditions as (-1) for one side and (+1) for the other side. Thus the name Minimax, because one side is trying to minimize the value (predicting the best moves the user can do), while the other side tries to maximize it (choosing the best moves to play as AI).

There are two main files in this project:  
- tictactoe.py: contains all of the logic for playing the game (rules), and for making optimal moves (Minimax adversarial search).  
- runner.py: contains all of the code to run the graphical interface for the game using the package *pygame*.

See full problem description here: https://cs50.harvard.edu/ai/2020/projects/0/tictactoe/

More info about Minimax here: https://cs50.harvard.edu/ai/2020/notes/0/#minimax

Usage:
```
python runner.py
```

Example:
<img src="https://cs50.harvard.edu/ai/2020/projects/0/tictactoe/images/game.png">
