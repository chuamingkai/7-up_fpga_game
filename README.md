# 7-up_fpga_game
## Description

The game is a physical and visual form of the verbal game, Seven-Up. Seven-Up is a game played by having players clap whenever the number (counting upwards between players) does not contain the digit, x and is not a multiple of x. If the numbers do contain or are multiples of the digit, the players are not allowed to clap. In the case that a player makes a mistake, the player would lose the game, crowning the opponent the winner.  

The interface of our game is thus simple, with buttons to replace the ‘clapping’ (choice made by players)  with two buttons, one (yellow button on the left) to indicate that the number is safe for one to clap, and the other to ‘not clap’ (blue button on the right).  The counting number would be displayed on the game interface through seven-segments. Using LEDS, the turn indicators and game result will be lit up accordingly.  Finally, there are three modes in this game, with the digits 3, 5 and 7 that can be chosen through switches located on the game console before the start of the game. 

## Logic flow

## Notes
Originally, we intended to include a timer in our game to limit the response time of the players. However, difficulties in the mainFSM and checker logic flow led us to scrap the timer due to time constraints.
The two folders, with_timer and no_timer include outdated code.

