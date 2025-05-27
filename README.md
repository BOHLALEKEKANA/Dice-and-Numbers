# Dice and Numbers

Here's a game plan:

Board: A 10x10 grid (100 squares), numbered 1 to 100.
Players: Two players, represented by colored tokens (red and blue).
Dice: A six-sided die with equal probability (1/6 per side). The die is rolled by clicking a button, and it moves the current player’s token.
Entry Rule: Players start at position 0 and must roll a 6 to enter the board at position 1.
Snakes and Ladders: Predefined snakes (move down) and ladders (move up) on the board.
Turns: Players alternate turns. The die roll determines movement, and snakes/ladders adjust positions.
Win Condition: First player to reach or exceed position 100 wins.

How to Play:

Objective: Be the first player to reach or exceed position 100 on the board.
Setup: Two players (Player 1: red, Player 2: blue) start off the board (position 0).
Entry: To enter the board at position 1, a player must roll a 6.
Turns: Players take turns clicking the "Roll Dice" button. The die shows a random number (1-6, each with ~16.67% probability).
Movement: If a player has entered the board, their token moves forward by the die’s value.
Snakes and Ladders:
Ladders (green lines): Move up to a higher position (e.g., 4 to 14).
Snakes (red lines): Move down to a lower position (e.g., 16 to 6).
Winning: The first player to reach or exceed position 100 wins. The game ends, and the roll button is disabled.
Display: The board shows numbered tiles (1-100), player tokens, snakes (red), ladders (green), and the die’s value. The status text indicates whose turn it is, the roll result, and any snake/ladder effects.

Notes:

The board is a 10x10 grid, with numbers increasing left-to-right on even rows (bottom-up) and right-to-left on odd rows.
Snakes and ladders are fixed and visually shown as red/green lines.
The die is fair, with each side (1-6) having an equal chance (1/6).
If a player hasn’t entered the board, they need a 6 to start; otherwise, their turn passes.
To play again, refresh the page.