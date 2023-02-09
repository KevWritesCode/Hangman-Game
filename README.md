# Hangman-Game
A simple Hangman game built using Python 3.x.

Technologies Used:

- Python 3.x

Description:

The Hangman game is a classic word guessing game where the player tries to guess the word by suggesting letters. The game is implemented using Python 3.11.1 and uses functions and loops to manage the game logic.

Key Parts of the Code:

- display_word function: This function takes the word to be guessed and the letters that have been correctly guessed so far and returns a string that represents the word with underscores for the unguessed letters.
- check_letter function: This function takes the word to be guessed, the letters that have been correctly guessed so far, and a letter input by the player and returns whether the letter is in the word and if it has been correctly guessed.
- game_loop: This loop allows the player to keep guessing letters until they either correctly guess the word or they run out of tries.
- try-except block: This block is used to handle any errors that may occur during the game. If an error occurs, the player is prompted to try again.

Design Decisions:

The design of the Hangman game was kept simple for ease of use. The user interface is minimal, consisting only of the word to be guessed and the prompt to enter a letter. The player can enter any letter and the application will check if it is in the word and if it has been correctly guessed.

The choice to use loops and functions was made because it allowed for the game logic to be easily managed and organized. The game logic is broken down into smaller, manageable parts making it easier to debug and improve upon.

Reflection:

Working on the Hangman game was a fun and educational experience. I was able to apply my knowledge of Python to build a functional and entertaining application. One of the challenges I faced was figuring out how to keep track of the letters that have been correctly guessed, but I was able to overcome this by using a list to store the correctly guessed letters.

I learned that even classic games like this can be implemented in a simple and efficient way using programming. Additionally, I learned the importance of considering user experience when designing a game.

Additional Resources:

- Python documentation: https://docs.python.org/3/
