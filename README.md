# Description of the Readme file

This a Markdown format file and during the editing of this file, I should at least commit it twice.

Basically, the lab2 code is about a card game that two players get one card each time from two separate card decks and compare the value of each other's card. And it will keep track of the result of each comparasion and eventually decide who is the winner or it is a tie.

The first class Card can generate cards of all suits and ranks, every instance of this class is a card.

The second class Deck creates a whole set of cards which is composed by 52 cards with ranks from 1 to 13 and suits from Diamonds to Spades. This class also has a bunch of tools to manipulate the whole set such as take off one card from the pile, shuffle the cards and add a new card.

The function play_war_game is the process of the game. It creates two players and two decks at the beginning and lets them get one card each time and compete the value of those cards. It accumlates the socre of each comparasion and gets a winner at the end of this game
