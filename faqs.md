The original Bingo mod is back! A simple game of advancement bingo.

![A game of Bingo in progress.](https://github.com/J78FDK42/Bingo/raw/main/screenshots/screenshot-in-progress.png "A game of Bingo in progress.")

A user can start a game of advancement bingo for players in the session. The game works with both vanilla advancements and/or custom advancements. Options for various game rules and card generation can be changed in the config files. Advancements are numbered starting from one and generated boards have a proper bingo number spread among all rows and columns.

## FAQs ##


### How to Play ###

[How to Play (video)](https://youtu.be/04HSqShVT68 "How to Play (video)")


#### Add players

* A player can type the `\bingo join` command to join a game of bingo
* A player can type the `\bingo add -player-` command to add another player to the game
* A player can type the `\bingo players` command to see a list of all players in the game


#### Start the game! 

* Open the Bingo Game Screen using the `'b'` key to choose game options
* When players are ready, a player can use the Game Screen to start a game of advancement bingo
* A player can also type the `\bingo start` command to start the game of advancement bingo
* A player can quit the game at any time using the `\bingo quit` command
* A game can be cancelled for all players at any time using the `\bingo stop` command
* The game status can be viewed at any time using the `\bingo started` command
* Bingo cards can be viewed using the `'o'` key or right-clicking a bingo card item
* Bingo cards can only be viewed after the game has started
* Player advancement progress is cleared when the game is started
* A player with op privileges can kick a player from the game using the `\bingo kick -player-` command


### Red vs. Blue Team Play ###

* A player can type the `\bingo join red|blue` to join the red or blue team
* A player can type the `\bingo add -player- red|blue` command to add another player to the red or blue team
* When a player types the `\bingo players` command each player name is displayed in their team color if any
* A player cannot switch teams once a game has started


### Key Bindings ###

The default keys for the bingo game can changed in the Minecraft Menu for Key Binds

* View Bingo Card: `'o'`
* View Game Screen: `'b'`
 

### Loot Generation ###

Game Screen option for Loot Generation on the Progress page using the `'b'` key
-OR-
* A player can type the `\bingo loot` command to toggle loot generation on or off
* A player with op privileges can toggle loot generation after the game has started
-OR-
Navigate and edit file: `config/bingo-common.toml` 


### Custom Loot Tables ###

[Custom Loot Tables (video)](https://youtu.be/qXyW3msLbgQ "Custom Loot Tables (video)")

Just extract the datapacks.zip file and drop the BingoLoot folder into your world save's datapacks folder to generate random loot during the game. You can customize the given loot by editing the square.json and winner.json files.

* BingoLoot/data/bingo/loot_tables/square.json
* BingoLoot/data/bingo/loot_tables/winner.json


### Advancement Datapacks ###

[Custom Advancements (video)](https://youtu.be/qXyW3msLbgQ "Custom Advancements (video)")

Just extract the datapacks.zip file and drop any or all collectables datapacks into your world save's datapacks folder and make sure custom advancements are enabled.

* Easy collectables datapack (100+ items!)
* Medium collectables datapack (100+ items!)
* Hard collectables datapack (100+ items!)


### Minecraft Game Commands ###


* `bingo start` starts the game
* `bingo stop` cancels any game in progress
* `bingo reset` same as `bingo stop` to cancel a game in progress
* `bingo add -player-` adds the player to the list of active players
* `bingo start` starts the game for all active players
* `bingo add all` adds all players in the session to the list of active players
* `bingo start all` starts the game for all players in the session
* `bingo players` lists all active players in the session
* `bingo add -player- red|blue` adds the player to the list of active team players
* `bingo join` adds the player to the list of active players
* `bingo join red|blue` adds the player to the list of active team players
* `bingo quit` cancels the player's game in progress
* `bingo kick -player-` removes a player from the game (requires op privileges)
* `bingo loot` toggles game loot generation on or off


### Game Rules and Config Files ###

Use the Bingo Game Screen using the `'b'` key
-OR-
Navigate and edit file: `config/bingo-common.toml` 

* Include/exclude recipe advancements in the game
* Include/exclude vanilla advancements in the game
* Include/exclude custom advancements in the game
* All players use the same bingo card in the game
* Any player advancement is marked completed for all players in the game
* Team players use the same bingo card in the game
* Team player advancement is marked completed for all players on the team


