# Word Guessing Game

## Overview
This project is an interactive game in Python using Jupyter Notebook. The player has to figure out a secret word that is randomly selected with a limited number of attempts. Players input one letter at a time, and correct guesses will reveal the position of the letter in the word. Incorrect guesses decrease the player's remaining lives.

## Project Components

### 1. Design
The game is designed to be interactive. The player is first greeted with a welcome message and rules of the game. Then there will be a row of blank underscores representing the secret word that needs to be guessed. The game will prompt the player for a letter and once validated, their progress will be updated with the guessed letter and remaining attempts. 

### 2. Data
Lists will be used as the word bank and to display the correctly guessed letters.
Sets will be used to track all the unique letters that the player has already used to prevent duplicates.
Strings are used to hold the secret word and the player's current guess while keeping track of the remaining lives.

### 3. Algorithms
A 'while' loop is used and continues running until the player has lives remaining and the hidden word has not been revealed. The conditional 'if/else' statements handles:
1. Validation Algorithm: checks if the input is a valid alphabet letter and hasn't been guessed yet
2. Matching Algorithm: Looks through the secret word using a 'for; loop to check if the guessed letter matches any index position.

### 4. Tools
1. Python 3: programming language for the game mechanics
2. Jupyter Notebook: Used to write and test the code
3. Git and GitHub: used for repositories and branches.

### 5. Communication
This project demonstrates how Python is applied to be interactive. Running the notebook from top to bottom with no erros demonstrates reliable programming.


