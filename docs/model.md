# Model

The bare-bones model of a game is the first portion which must be designed. It is the foundation by which players will either enjoy the game or find it ignorable.

The best approach in designing the model for a game is to specify the requirements which must be met for the game to achieve success. This method will hold true for the following documentation, with CITIZEN's solution to these problems detailed accordingly.

## Requirements

#### MUST requirements:

The ultimate MUST is that the game must be fun. It is believed that these elements are primary in achieving such a goal.

1. The game must be simple to play.
2. The game must have clear goals for each player.
3. The game must not take longer than an hour.
4. The game must allow the chance for inexperienced players to win.
5. The game must allow for simple strategic optimization.
6. The game must be flexible enough to deal with various numbers of players with only small changes.
7. The game must hold a theme which correlates closely with gameplay.

#### DESIRED requirements:

1. The game should avoid presenting chance explicitly as an important game element.
2. The game should not allow for the [Kingmaker scenario](https://en.wikipedia.org/wiki/Kingmaker_scenario).
3. The game should hold strategic complexity which surpasses human ability to perfectly solve.
4. The game should follow a model wherein the rate of increasing win percentage exponentially decreases as gameplay experience is gained.

## Analysis

#### Simplicity

CITIZEN is designed to be based on a very simple gameplay model. The rules can be compressed easily with few caveats.
For example, if explaining the game to new players, it might go as follows:

* "We are all traders in the outer realm of space trying to buy citizenship. That means that you will be buying supplies and gaining special abilities based on the supplies you have."
* "During a round, when it it your turn, place one of your money cards face down on a merchant. You need to play a card on each merchant before you can play a second card on any merchant. Once all cards have been played, you will get to choose a supply from one merchant where you paid more than other players!"
* "Look at the combination of materials you have and check the boards to see what special ability you get for the next round."
* "During the final round, the player who outbids the next highest player by the greatest amount (on any merchant) wins their citizenship and the game is over."

One beauty of CITIZEN is that simplicity is not sacrificed on the altar of strategic complexity. This is achieved by encapsulating simple exterior rules on the special ability boards. These abilities are not necessary to know in order to have a basic understanding of the game. Similarly, these external rules are designed so that there can be no confusion over their usage.

#### Goals

The depth of strategic paths in CITIZEN is rich, which can often be confusing to players which do not know how to start. For this reason, the "Empire Merchant" was developed, which sets up a good bidding goal for players who do not have experience with the game. (If you have not read the rules yet: the Empire Merchant grants an extra money card to the player who wins that specific merchant during the round).  

#### Game Length

The game lasts 45 minutes when an average amount of discussion is happening. It can be as short as 25 minutes when players are new to the game or do not use much relational strategy.

One neat part about learning this game is that there is always a new thing to try for the next time around. Aiming for new and different raw materials in your cargo hold proves to be very enjoyable because you get to test out a new strategy each game. Relatively short game times (30 minutes) are optimal for this model.

#### Chance

There is no explicit inclusion of chance into the CITIZEN model. This requirement is on account of highly analytical people who dislike games including chance.

The game includes no more chance than does chess or checkers. However - people are unpredictable. The element of secret player decisions simulates chance effectively so that the game model is not broken. See the following discussion on the Kingmake scenario.

#### The Kingmaker Scenario

Game theory tells us that determinism in a multiplayer game leads to the Kingmaker scenario - when a player realizes they are unable to win, they may break the game by helping another player.

This problem of determinism and the Kingmaker scenario is solved by way of player-oriented chance and the strategic complexity. In CITIZEN, all cards are played face-down, which provides the element of player-oriented chance. Consider the senario where a player has two card in his hand, and I know what both of them are. If he plays one card onto a merchant, I cannot know which card he played. Though there is no institutionalized chance in this decision, the effective result of putting secret decisions into the hands of players is the same as if a die were rolled or a deck was shuffled. In many ways, this sort of chance is much better than explicit game chance because most players think they are good at predicting the decisions of others, even though they are not.

By effectively reintroducing chance into the game through player decision, the Kingmaker scenario is avoided. Of course, this solution only applies as long as there is a chance for every player to win during the final round. This design point is the most innovative portion of CITIZEN's architecture. Players will progress during each round, even if they play poorly. The special abilities and money cards are balanced so that every player has the potential ability to win during the final round if they are able to convice other players to play cards in certain ways. Abilities that are detrimental to single players are designed to be very limited in their effectivity so that players are not able to gang up on one person. These elements, when combined, fully solve the Kingmaker scenario.
