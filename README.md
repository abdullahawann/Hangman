# Hangman

The Hangman game designed in assembly language is a classic word-guessing game where players attempt to guess a hidden word by suggesting letters. The game is implemented using assembly language to provide a low-level, efficient, and interactive experience.

The game begins by selecting a random word from a predefined word list or by allowing the user to input their own word. The chosen word is then displayed to the player as a series of underscores, representing each letter in the word.

The player is prompted to input a letter guess. The assembly code checks whether the letter is present in the chosen word. If the letter is correct, the corresponding underscores are replaced with the correct letter at the correct positions. If the letter is incorrect, a part of the hangman's body is drawn on the screen, indicating the player's progress towards losing the game.

The game continues until the player either successfully guesses the entire word or the hangman is fully drawn. If the player successfully guesses the word, a victory message is displayed. If the hangman is fully drawn, indicating that the player has run out of guesses, a defeat message is shown.

Throughout the game, the assembly code handles the logic for checking the validity of input, updating the display, tracking the remaining guesses, and determining the outcome of each round. The code may include functions for input validation, word selection, drawing the hangman, and checking for win/loss conditions.

The Hangman game implemented in assembly language offers a challenging and interactive experience, utilizing low-level code for efficient execution. It demonstrates the capabilities of assembly language in creating simple yet engaging games.
