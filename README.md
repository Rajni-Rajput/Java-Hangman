# Java-Hangman
I created a Hangman guessing game using basic Java.

For this problem, you will implement a variation of the classic wordgame Hangman. For those of you who are unfamiliar with the rules, you may read all about it here. 
(https://en.wikipedia.org/wiki/Hangman_(game)) 
In this problem, the second player will always be the computer, who will be picking a word at random.

In this problem, you will implement a class, called HangMan, that will start up and carry out an interactive Hangman game between a player and the computer. 

# Problem Description :
The computer must select a word at random from the list of available words that was provided in words.txt. 
The functions for loading the word list and selecting a random word have already been provided for you.
The game must be interactive; the flow of the game should go as follows:

At the start of the game, let the user know how many letters the computer's word contains.
Ask the user to supply one guess (i.e. letter) per round.
The user should receive feedback immediately after each guess about whether their guess appears in the computer's word.
After each round, you should also display to the user the partially guessed word so far, as well as letters that the user has not yet guessed.

# Some additional rules of the game:
A user is allowed 7 guesses. Make sure to remind the user of how many guesses s/he has left after each round. Assume that players will only ever submit one character at a time (A-Z).
A user loses a guess only when guesses incorrectly.
The game should end when the user constructs the full word or runs out of guesses. If the player runs out of guesses (s/he "loses"), reveal the word to the user when the game ends.
