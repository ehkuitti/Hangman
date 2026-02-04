# Hangman

<img width="405" height="371" alt="kuva" src="https://github.com/user-attachments/assets/c796ad35-b920-4562-a9e3-59aee34f9221" />



This game is a Python implementation of the game classic "The Hangman". This
implementation is developed using Python 3.10 with tkinter in the front-end.

The game starts by asking whether the player wants to by play himself/herself or
with someone. If the player chooses to play alone, the game will randomly
select a word from a pre-determined list of words. This is done by generating a
random value using randrange and then choosing the word in the corresponding
index on the list. If the player plays with someone, the other person decides
the word to be guessed by inputting it into a tkinter Entry object.

The player inputs letters by clicking on tkinter buttons with letters on
them. In case of clicking a correct letter, the game will insert it into text
box (in alphabetical order). If the letter is incorrect, the letter gets
disabled and cannot be clicked again.

## Game instructions

When the game starts, player can choose either to play singleplayer game or
multiplayer game by pressing the buttons on the screen.

## Singleplayer game

If player chooses to play the singleplayer game, the program randomly chooses a
word from a list that the player has to guess to win.

## Multiplayer game

If player chooses to play the multiplayer game, the game can be played with
someone else. After pressing the multiplayer button, an entry appears on the
screen and another player can enter a word that the other player has to guess to
win. The word can be 1-11 letters long and must contain only letters. The choose
button must be pressed for the game to start.

## The game functionality

A keyboard appears on the screen and by pressing the letter the player wants
to guess, the program will check if the letter is found in the chosen or
randomly drawn word. Player has 11 wrong guesses before the game ends. If the
guess is wrong, a hangman picture will appear on the screen and player has
one guess less. If the guess is correct, the letter will appear on the screen at
the correct spot in the word. If player guesses the word before getting 11
wrong guesses, the game has been won. When the game is won or lost, another
screen appears with a text according the end result. On the screen also
appears a quit button that shuts the program once clicked.
