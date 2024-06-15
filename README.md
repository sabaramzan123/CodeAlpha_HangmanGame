# CodeAlpha_HangmanGame
This Python script is a text-based Hangman game where a player guesses a randomly chosen word one letter at a time. The key features include:

Word Selection: The get_word() function picks a random word from a predefined list (wordsList).
Game Display: The display_hangman(tries) function shows the current state of the hangman based on the number of incorrect guesses.
Game Loop: The play(word) function handles the game mechanics, including user input, updating the word display, and tracking guessed letters and words.
Replay Feature: The main() function starts the game and allows the player to play multiple rounds by prompting them to play again after each game.
Players guess letters or the whole word, with a limited number of incorrect guesses (6 tries). Visual feedback is provided via a progressively complete hangman graphic. The game continues until the word is guessed or the player runs out of tries.
