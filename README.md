# 8-15-24-puzzle
Solving the 8, 15, and 24 puzzle with the A* algorithm. Guided by choosing 1 of 3 heuristics: Manhattan, Misplaced Tiles, Weighted A*

## What is 8 puzzle?
The 8-puzzle is a square board with 9 positions, filled by 8 numbered tiles and one gap. At any point, a tile adjacent to the gap can be moved into the gap, creating a new gap position. In other words the gap can be swapped with an adjacent (horizontally and vertically) tile. The objective in the game is to begin with an arbitrary configuration of tiles, and move them so as to get the numbered tiles arranged in ascending order either running around the perimeter of the board or ordered from left to right, with 1 in the top left-hand position. An example scenario is shown below.

## Initial and Goal State
![Initial/Goal States](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.kUUWG9bP3Y10JJfdh2pSfgHaDL%26pid%3DApi&f=1)

## 15 and 24 puzzle
The  15 and 24 puzzle work as soved with the same goal in mind as the 8 puzzle, but with a bigger board. 15 puzzle has a 4x4 board and 24 has a 5x5 board.

## References
https://www.8puzzle.com/8_puzzle_problem.html
