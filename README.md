# Blackjack
A fully functional blackjack game utilising a standard GUI.
This project was my first introduction to developing GUI using tkinter, and was one of my favourite projects whilst learning Python

When the program is run, the Black Jack main window opens. This window, and the subsequent frames, labels and buttons were generated using the tkinter interface.
A list of tuples containing a card value and its associated image is generated. 
The player is randomly assigned two cards of a given suit and value, and the dealer is assigned one card

As per normal Black Jack rules, cards 1-10 have the value of their stated number.
King, Queen and Jack have the value of 10, and Aces can be either 1 or 11.
The summation of the player's card values is stated in a frame on the left of the card image. 
The aim of the game is to get the values of the cards to be as close to 21, without going over 21 (referred to as "going bust").

If the player wishes to add to the value of their two cards, they can click on the "Player" button to randomly be assigned another card.
If the player goes bust, the dealer automatically wins.
Once a player is happy with their value, they click the "Dealer" button to draw the dealer's cards.
The closest player to 21 wins, or it is a draw if both player's cards have the same value.

The "New Game" button will start a new game and reassign the cards to both the player and the dealer.
The "Shuffle" button will randomly shuffle the cards which have not yet been dealt in the deck. 

This project allowed me to become fully proficient in using tkinter to build interactive windows, as well as reinforcing my knowledge of efficient and appropriate function creation in programming to streamline to running and developing of code.

