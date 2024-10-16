# claw-machine-game-DE1SoC
ECE243 Final Project

Operating the Game

Connect to DE1-SoC board with PS2-Keyboard to begin. The game starts with a start page displaying the game title, designers and some input messages.
From the start page, you can toggle hard mode on or off based on the state of switch 0. Hard mode will increase the size of the prizes making picking up the prizes more difficult.
Clicking the 3 key on the keyboard will begin the game.

![Start Screen](clawmachinestart.png)

The user uses keys A and D to move the claw left and right respectively and the claw will continuously move in that direction until new input is provided.
The key S is used to pick a location to drop the claw.
The claw will descend and rise again and drop off the prize (or lack of one) to the left prize section.
A corresponding win or miss noise will play through the speakers and the user can pick up the next prize.
If the selection is successful the score in the top right will increase by 1 and if unsuccessful, the score will decrease by 1 but never go below zero.

![Mid Game](clawmachinegame.png)

Once all five prizes are selected, a congratulatory message will display with the final score in the top right and the option to play again with the 3 key.
Hard mode can be toggled from the win page for the next round.

![Win Screen](winscreen.png)
