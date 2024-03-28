# TicTacToe
## Overview of The Game
The game of TicTacToe is a game played by two players, it consists of a 3x3 grid which contains 9 cells.
|*|1|2|3|
|-:|:-:|:-:|:-|
|c|_|_|_|
|b|_|_|_|
|a|_|_|_|

Players play using symbols "X" or "O".
|*|1|2|3|
|-:|:-:|:-:|:-|
|c|X|_|_|
|b|_|O|_|
|a|_|_|_|

To win, one must get a 3 vertical/horizontal/diagonal cells to have the same symbol ("X" or "O"), in this
case the symbol will be that of the player who hopes to win.
|*|1|2|3|
|-:|:-:|:-:|:-|
|c|X|_|_|
|b|_|X|O|
|a|O|_|X|

In the above case, player X has won, by filling consecutive diagonal squares with the symbol X.
|*|1|2|3|
|-:|:-:|:-:|:-|
|c|X|_|_|
|b|O|O|O|
|a|_|_|X|

In the above case, player O has won, by filling consecutive horizontal squares with the symbol O.
If all 9 cells are filled and no player has won, then the game results in a draw.
|*|1|2|3|
|-:|:-:|:-:|:-|
|c|X|O|X|
|b|O|O|X|
|a|X|X|O|

In the above case, the game ends in a draw as no player has won and all 9 cells are filled up.

## Overview of Repository File Structure:
1. index.html
2. README.md
3. script.js
4. settings.js
5. style.css
6. variables.js
7. LICENSE.txt
######
1. index.html:
  This is the entry point of the program where all game visuals are displayed.
2. README.md:
  This mostly contains information about how the game works, including links to relevant files.
3. script.js:
  For game functionality and implementation of game logic.
4. settings.js:
  Contains code to let users customize the game to their preference.
5. style.css:
  Contains the styling of the game.
6. variables.js:
  Contains game variables that are often used in different parts of the program.
7. LICENSE.txt:
  This contians the license of the repository which dictates how it can/cannot be used.
8. ComputerAsFirstPlayer.md:
  This contains an in-dept explanation of the thought process which led to the creation of an unbeatable computer first player.
9. ComputerAsSecondPlayer.md:
  This contains an in-dept explanation of the thought process which led to the creation of an unbeatable computer second player.