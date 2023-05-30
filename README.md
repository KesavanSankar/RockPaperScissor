# RockPaperScissor
A popular child's game played by using hand signs; frequently used to break ties.

This is a simple implementation of the Rock-Paper-Scissors game where a player competes against the computer. The game is played for a specified number of rounds, and the winner is determined based on the choices made by the players.

## How to Play

1. Run the `game()` function to start a new round.
2. Enter your choice of either "Rock", "Paper", or "Scissors" when prompted.
3. The computer will randomly select its choice.
4. The winner of the round is determined based on the following rules:
   - Rock beats Scissors
   - Paper beats Rock
   - Scissors beats Paper
   - If both players choose the same option, it's a tie.
5. The winner of each round is displayed, and the overall score is shown at the end.

## Code Explanation

- The `game()` function is responsible for running a single round of the game. It prompts the player to enter their choice, generates a random choice for the computer, determines the winner, and updates the scores.
- The `player_choice()` function prompts the player to enter their choice and returns the entered choice as a string.
- The `computer_chance()` function generates a random choice for the computer player from the available options.
- The `player_details()` function prompts the user to enter the name of the first player and returns a tuple containing the names of both players.
- The `points_player()` and `points_computer()` functions update the scores of the players based on the outcome of each round.
- The `options_available()` function returns the available options for the player's choice.
- The main code section allows the user to specify the number of rounds to be played and runs the game for the specified number of rounds.

## Running the Code

1. Make sure you have Python installed on your system.
2. Copy the code to a Python file (e.g., `rock_paper_scissors.py`).
3. Run the Python file using a Python interpreter (e.g., `python rock_paper_scissors.py`).
4. Follow the on-screen prompts to play the game.

Enjoy playing Rock-Paper-Scissors!
