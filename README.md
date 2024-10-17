# Mine Sweeper

A **Minesweeper** game implementation.

## Features

- Classic Minesweeper gameplay
- Easy, Medium, and Hard difficulty levels
- Timer and score tracking

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/microkom/mine_sweeper.git
   
2. Open the project directory:
   ```bash
   cd mine_sweeper
 
## Usage
- Open the index.html file in your browser to start the game.
- Use the mouse to uncover squares and flag potential mines.
- Clear the board without triggering any mines to win!

## Technologies Used
- HTML
- CSS
- JavaScript

## Objective
The objective of the game is to uncover all the squares on the grid that don’t contain mines, without detonating any of the mines.

## Game Setup
- Grid: You start with a grid (typically 9x9, 16x16, or 30x16) filled with covered squares.
- Mines: A certain number of mines (bombs) are randomly hidden under the squares.

## Basic Rules
Uncover a Square: Click on a square to uncover it.

- If the square does not contain a mine, it will show a number indicating how many mines are adjacent to that square (in the 8 surrounding squares).
- If you click on a square containing a mine, you lose the game.
- If the square has no adjacent mines, it will be blank, and the game will automatically reveal adjacent empty squares.
- Flagging Mines: You can mark squares you suspect contain mines by right-clicking on them twice. This places a flag to help you remember where the potential mines are.

Using Numbers: The numbers revealed when you uncover a square tell you how many mines are in the adjacent squares. You can use this information to deduce the location of nearby mines.

## Strategy
Identify Safe Areas: If you uncover a square with a "1," and only one adjacent square remains covered, that square is most likely a mine. Mark it with a flag.
Expand Known Areas: Use uncovered squares with numbers to work out where mines might be located and which squares are safe to click.

### Winning the Game
To win, you must uncover all the squares that do not contain mines, while avoiding the ones that do. Once all non-mine squares are uncovered, you win the game.
Losing the Game

If you click on a square containing a mine, it will explode, and the game ends.

### Difficulty Levels:

- Beginner: 9x9 grid with 10 mines.
- Intermediate: 16x16 grid with 40 mines.
- Expert: 30x16 grid with 99 mines.
  
Each difficulty increases the grid size and the number of hidden mines, making the game more challenging.
