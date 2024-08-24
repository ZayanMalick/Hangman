# Hangman 

## Introduction:
<div align="justify">
This is a simple Python implementation of the classic Hangman game. The game randomly selects a word, and the player must guess the word one letter at a time. The player has a limited number of attempts to guess the word correctly before the game is over. </div>


## Project Structure:

The project contains three Python files:

### main.py: 
This is the main file that contains the logic of the game. It imports the word list from hangman_words.py and the visual stages and logo from hangman_art.py.

### hangman_words.py: 
This file contains a list of words (word_list) that can be randomly selected as the secret word for the game.

### hangman_art.py: 
This file contains the ASCII art used in the game, including the visual stages of the Hangman and the game logo.

## How to Play 🎮:

1. Run the main.py file.

2. The game will display the Hangman logo and the word as a series of blanks (_).

3. Guess letters one at a time by typing them in.

4. If you guess a letter correctly, it will replace the corresponding blank in the word.

5. If you guess incorrectly, you will lose a life, and the Hangman figure will start to appear.

6. You have a total of 6 lives. If you guess all the letters correctly before losing all your lives, you win the game. If you lose all your lives, the game is over, and you lose.

## Installation:

To run this project, you need to have Python installed on your machine. Clone this repository and navigate to the project directory, then run the following command:

    python main.py

## Contributing:
Contributions are welcome! Please fork this repository and submit a pull request.

## License:

This project is licensed under the MIT License. See the LICENSE file for details.
