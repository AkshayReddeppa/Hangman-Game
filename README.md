# Hangman-Game
This Python code implements the classic word guessing game, Hangman. The player tries to guess a hidden word, one letter at a time. If they guess incorrectly, a part of a stick figure is drawn. The game ends when the player guesses the word correctly or the stick figure is complete.
Key Features:

Random Word Selection: A random word is chosen from a list of words.
Letter Guessing: Players input letters to try and guess the word.
Hangman Drawing: A stick figure is drawn progressively as the player makes incorrect guesses.
Win/Lose Conditions: The game ends when the player guesses the word or the stick figure is complete.
Code Structure:

Word Selection: A function to select a random word from a list.
Game Loop: The main loop that handles player input, letter checking, and game state updates.
Display Function: A function to display the current state of the game, including the guessed letters and the hangman figure.
Win/Lose Conditions: Checks to determine if the player has won or lost.
