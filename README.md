- Take a user story per pair and implement feature tests

- Swap pairs and review the feature test code

- Swap back and implement unit tests for the feature tests

- Fix conflicts and review the code

##### USER STORIES

**place_ship_spec**
As a player
So that I can prepare for the game
I would like to place a ship in a board location

**board_spec**
As a player
So that I can play a game thats fun
I would like to play on a 10x10 grid

**place_ship_spec**
As a player
So that I can have a coherent game
I would like ships to be constrained to be on the board

As a player
So that I can have a coherent game
I would like ships to be constrained not to overlap

As a player
So that i can win the game
I would like to fire at the board

As a player
So that I know when to finish playing
I would like to know when I have won or lost

As a player
So that I can consider my next shot
I would like an overview of my hits and misses so far

As a player
So that I can play against a human opponent
I would like to play a two-player game where i am able to fire at my opponents board

**battle_ship_spec**
As a player
So that I can play a more interesting game
I would like to have a range of ship sizes to choose from

As a player
So that I can create a layout of ships to fox my opponent
I would like to be able to choose the directions my ships face in

NOTE: Firing in the same place twice should be checked!