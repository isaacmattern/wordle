# **Wordle Solver**

### Python project by Isaac Mattern

[Wordle](https://www.powerlanguage.co.uk/wordle/) is a game where the objective is to correctly guess a 5-letter word in 6 tries or less. Each time a player submits a guess, the game highlights each letter in the word in

- green, if the letter is in the word and in the correct location in the word
- yellow, if the letter is in the word, but not in the position where the user guessed
- gray, if the word does not contain the letter at all

This project is an attempt to use a list of the 12,972 5-letter words which are valid Wordle guesses and some Python magic to solve some Wordles. I will generate an answer by randomly selecting an actual Worldle solution from the list of 2,315 words on Wordle's website, but the program will only "know" a list of valid guesses. This is effectively the same as a human anyways, since if you guess an invalid word on Wordle, you don't lose your turn.

I will be attempting to devise different algorithms to best solve Wordle.
