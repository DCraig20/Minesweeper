# Minesweeper
Minesweeper coded in Java

My Minesweeper that I programmed for fun over the summer 2021 to challenge myself and learn some more programming techniques. I was able to achieve this without looking up any logic. The only help I needed was syntactic and from the documentation.

I decided to have some fun over the summer and make minesweeper. Play like any normal minesweeper game.

The number in each box represents how many mines are in the 8 boxes touching that box.

To start the game, run MinesweeperDriver.java and enter valid inputs. 

When the game starts, it asks for a row count, column count, and number of mines. Then, a jframe window with the game opens up. The box size is based on the width and height of the grid of boxes.

Left click to reveal a box, right click to flag (yellow). Correctly flagged mines will be colored orange. Incorrectly flagged mines will be colored pink. You win when you flag all of the mines and reveal all other boxes. The only boxes left are flagged mines. Pressing r at any time will restart the game, keeping the same board dimensions and mine count. To change these, run the program again.

The code creates a 2D array of boxes. Each box is an object of the Box class. It contains parameters including (but not limited to) nunber of adjacent mines, where it is in the 2D array, is it a mine, and is it flagged. To reveal boxes, I used recursion. I reveal the called box. Then, I check that there are zero adjacent mines. If there are, I run cases for each box position (middle, edge, corner), and then call the method again. 

I encourage viewers to look at this code and try to learn from it.

 - Daniel Craig
