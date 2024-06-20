# Blackjack Strategy Evaluator

Program that evaluates and suggests strategies for playing Blackjack based on mathematical probabilities. Calculates the expected value (EV) of different player actions (stand, hit, double, split) and simulates the dealer's probabilities to provide optimal playing strategies.


## Features:

-Calculate the dealer's probabilities for reaching different totals.

-Evaluate the player's hand for optimal moves (stand, hit, double, split).

-Simulate the entire game to provide basic strategy recommendations.

-Output the expected values for each action.



## Options:

1. Dealer probabilities: Calculate the dealer's probabilities for reaching different totals with various up cards.
   
2. Player hand: Evaluate the player's hand against a specific dealer up card and print the expected values for each action.
   
3. Whole game: Simulate the entire game and provide basic strategy recommendations.




```main``` initializes the deck, provides a menu for the user to choose options, and calls appropriate functions based on the user's choice.

```player_stand```: Calculates the expected value when the player decides to stand.

```player_hit```: Calculates the expected value when the player decides to hit.

```player_double```: Calculates the expected value when the player decides to double down.

```player_split```: Calculates the expected value when the player decides to split pairs.

```dealer```: Simulates the dealer's play and calculates probabilities of reaching different totals.

```max2```: Returns the maximum of two values.
