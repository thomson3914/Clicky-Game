# Clicky Game

This app is a memory game built with React.js. The user's goal is to click on each card only one time until each card is clicked. There are 12 total cards that shuffle automatically on each click, making it more difficult for the user to remember which cards they have not clicked.  To add to the challenge, each card is an animated gif.

## Live Site:
https://thomson3914.github.io/clicky-game/

## Demo
![Home.html](screenshot.gif)

## How it works
* The user begins the game by clicking on card.
* After each click, the game shuffles the cards using an NPM package called Shuffle-Array and checks if the user has selected the card before.
* If they have selected the card before, it will trigger an end game condition.
* If they have not selected a card, it will increase the current score.
* If the user reaches 12, the game restarts.
