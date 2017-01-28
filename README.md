# RubyConf India 2017 Contest

## BlackJack 

### Contest start: 28th Jan 2017 - 10:00 am
### Contest end:  29th Jan 2017 - 9:00 am

## Prize: Top three winners will get an iPad Mini

### Problem Statement:

Blackjack is a popular card game played against a Dealer. In this card game the Player is trying to beat the Dealer.

#### Deck:

The game is played with 4 or more decks containing 52 distinct cards in each (Face values : A, 2-9, J, Q and K; Suits : D,C,S,H)
The entire deck is shuffled before the start of the game.

#### Beginning:

Player and Dealer are initially dealt 2 cards each. Only one of the Dealer's cards is visible to the Player, the other is hidden. All the cards of the Player are visible to everyone at all times.

#### Turns:

Player plays first, followed by the Dealer.

#### Player's Turn:

The Player could then choose to HIT (ask for another card) or STAND (no more cards).

If the Player chooses to HIT and total score crosses 21 they get busted.

The Player's option to choose continues till they get busted, or they choose to STAND or they obtain a score of 21 (also known as Blackjack).


#### Dealer's Turn:

When the Player completes their turn and the Player is not Busted, the Dealer then has to

* HIT themself if their score is less than <=17 until they reach a score >17
* STAND if their score >17

#### Scoring:

Face cards (Jacks, Queens and Kings) are worth 10 points. Aces are worth 1 or 11, whichever is preferable. The other cards are worth their number.
A person's score is the sum of the values of the cards in their hand.

### Ending:

The Player is busted. The Dealer wins.
The Dealer is busted. The Player wins.
Both the Player and Dealer obtain a BlackJack. The game is a draw.
In other cases, the person with a score closer to 21 wins.
When both Player and Dealer have the same score, the game is a draw.


### Game Rules

The solution to the problem should be object oriented. It should be solved in Ruby. 
P.S: We are not looking for the complete solution to the problem, but are looking for one’s approach at solving it.

Some features of the solution carries more weightage which include:

- Unit testing the solution
- Idiomatic Ruby code
- Good coding practices - S.O.L.I.D
- Object oriented approach - Domain modelling

P.S: You can reach out to any Gojek folks for clarification of the above problem.

### Submitting the solution

Complete the solution. Push the code to your github account and tweet us the link to the repository mentioning @GojekTech with Hashtag #RubyConfIndia

