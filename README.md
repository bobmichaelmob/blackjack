# javaprogrammingproject

Rules of the Game
1. Shuffle the cards (52 in number)
2. Player picks 2 cards from the deck.
3. Every player calculates the total value of the cards in hand.
4. The Game Decision system (GDS) decides who wins or lose based on the total
of the player. (GDS check whose total is close to 21)
a. If player’s total < 17: player’s hit (pick a new card)
b. if player’s total > 21: player’s bust (they are out of the game)
c. if player’s total > 17 and total < 21: player’s stick
5. GDS says game is over if
a. every player sticks
b. all players hit exactly 21
c. Only 1 player is left in the game and others have gone bust.
6. A winner emerges if everybody has gone bust or hit 21, except one person’s
total is close to 21.

1. Read project Question (story) and identify what the project is about and what
needs to be done. 30 mins
2. Discuss the project and clarify project goals in term of features, functionalities
and entities. 1 hour
3. Implementation procedure/schedule
a. Set up version control system and confirm okay
b. State all entities and their functionalities.
c. Carry out Modelling of (a) in UML (use draw.io).
d. Split implementation of the design
e. Commence project implementation in IntelliJ IDE as per UML design.
f. Use TDD - implement Test classes before method implementation.
g. Review the implementation afterwards.

Top Level Plan Reminders
1. Commit codes to gitlab for every
function(method) implemented
after testing and confirmed okay.
1. 2. Use pull request to ensure pair
verify codes before merging with
the main branch.
2.
3. Review should hold after every class
is implemented.
Card
1. A card has a suit attribute
2. A card has a value attribute
Black Jack
There are 52 cards.
There are 4 suits.
There are 13 values.
Each card belongs to 1 suit and has 1 value.
Conditions for our program
A.
1. # of players must be > 1 and <= 6
2. Default # of players is 3 (if not set in the program)
B.
1. Every player’s step should be log (by displaying on the screen)
2. Winning player should be displayed on the console.
C. Possible game strategies
1. Default
2. Always hit
3. Always stick
4. Risk-based strategy
D. Game shuffling
1. State shuffling mechanisms (algorithm)
2. Implement (1)
3. Program to select any card shuffling algorithm @ runtime.
