# tetris
Tetris coded with HTML5 and Javascript / jQuery using <canvas>.

## Steps finished.
* Added a grid method : drawing a tetromino square on the grid.
* Added a grid method : generate new tetromino.
* Added a grid method to make fall the active tetromino.
* Added a grid method to generate a new tetromino when the active tetromino cannot fall no more.
* If a new tetromino cannot be generated because the space is already occupied, game is over.
* We can now move the tetromino to the left or right.
* We can now accelerate the tetromino's fall by pressing the down arrow key.
* Fixed a bug that allowed to move the active tetromino left or right through
  immobile tetromino's squares.
* The player can now modify the active tetromino's state by pressing the up arrow key.
* Fixed a bug that allowed tetrominos to sometimes go through others tetrominos.

## To do.
* Remove a line when it is fully filled with immobile squares.
* Add a text message when the game is over.
* Add a random color to the tetrominos.
* Add a border to the tetromino squares.
* Top score system.
* To fix : if a player modifies the active tetromino's position while it is in the top of the grid,
  squares can be deleted if they go outside of the grid.

## To commit.
