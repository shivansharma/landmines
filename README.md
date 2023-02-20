Create a console application (no UI necessary) for a game in which one player moves a
single piece around a chessboard. Other than the use of a chessboard, there are no
similarities between this game and chess.
Instead the rules of the game are as follows:
• The board is 8 by 8 in size
• A player starts on the bottom-left square
• A player can move their piece up, down, left or right one square by entering U,
D, L, or R respectively
• A random number of squares are ‘landmines’
• The aim of the game is to get to the top side of the board without hitting more
than 2 landmines
• Following each move the game displays the new location and whether any
landmines were hit, plus whether the game has been lost (more than 2 land
mines hit) or won (reached the top of the board)
The game should be coded in C# using automated testing and SOLID principles
that ensure the game can be extended in the future without compromising development
efficiency or quality. It is more important to demonstrate proficiency in these areas than
to complete all the functionality described above.
Candidates can concentrate on coding the ‘happy path’ only and assume all input is
correctly formatted.

## How to run 
* Go inside Minefiled.app project and run 
* dotnet run 
* This will trigger the console app and you will see the options to play the game. 

## Controls:
* Up Arrow/U - Move player up
* Down Arrow/D - Move player down
* Left Arrow/L - Move player left
* Right Arrow/R - Move player right
* Enter - Reset game
* Esc - Exit game

## Main features:
* Tiles generated on X and Y axis to form a chessboard
* Hidden mines on tiles, allocated randomly
*	Player starts at a randomly allocated tile at the bottom of the board and needs to reach a randomly allocated tile at the top of the board
*	Player is allocated a fixed number of lives
*	Player loses a life if they land on a mine
*	Player can move up, down, left, and right
*	Console interface displays board, current player position, number of lives left, and number of moves taken
*	Final score is determined by the number of moves taken to get from start to finish

## Additional features:
*	Show how close the player is to a mine to add an element of strategy where the player has an idea where the mine may be and has a chance to avoid it


