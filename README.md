# Pandemic-Scenarios
Pandemic Scenarios
Summary
Pre-defined placement of cards (deck stacking) such that every game starts with the same board setting, country infection progression and pandemic timings.  This will allow:
Re-playable games that will have a known difficulty (I could have won if I had done this one thing differently)
Tournaments where everyone must play against the same game and thus creates an even playing field.
Story telling (like Pandemic Legacy) since the general flow of how the game will progress will be known to the designer of the scenario at scenario creation time.
Future Considerations
The basic idea of being able to stack the deck without knowing what the order is can be applied to almost any card-based game.  This also leads itself very well to building communities where people contribute scenarios to a central server for people to download and play.
Basic Requirements (Android Application)
Program must be able to identify card by passing the card over the phone camera (card back to player, card face to camera)
Program must be able to load a “scenario”, best described as an ordered list of cards
Program must indicate to the player where to place the card in the deck.  
Note:  Need to think through ideas to make stacking simple and to minimize mistakes (sorting alg. Trade offs where performance is not the only consideration)
Player create multiple stacks that are then combined when finished.  i.e. Stack: 1, Positions 3
Player only put cards on top or bottom of deck and then re-stacks until deck is properly sorted
Program “checks” off that card from the list (in case the same card is represented multiple times) and then proceeds to step 1
Once all cards are arranged, there may be a final “clean up” task to finalize the card stacking (depending on the sorting alg. Used in step 3)
Task Outline
