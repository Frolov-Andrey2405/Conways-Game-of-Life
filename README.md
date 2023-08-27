# Conway's Game of Life Simulation

Conway's Game of Life is a cellular automaton used to simulate and create interesting patterns based on simple rules. This automaton was invented by mathematician John Conway in 1970 and became famous through Martin Gardner's "Mathematical Games" column in Scientific American. Today, programmers and computer scientists enjoy this interesting visualization rather than an actual "game".

The game board in "Life" is a two-dimensional grid of cells. Each cell can be alive or dead, and it follows three simple rules:

1. A living cell with two or three living neighbors remains alive for the next step.
2. A dead cell with exactly three live neighbors comes alive in the next step.
3. All other cells die or remain dead in the next step.

The state of a cell in the next step depends only on its current state. Cells do not retain information about previous states. There is a lot of research on the patterns that can emerge on the board based on these simple rules.

## How to Experience

1. Run the program in a compatible environment.
2. Observe as the simulation unfolds, revealing stunning patterns that evolve over generations.
3. Witness the mesmerizing interplay of life and death as cells follow the rules of the game.

## Features

- Engage with Conway's Game of Life, a timeless mathematical and computational marvel.
- Discover the enchanting emergence of intricate patterns from elementary rules.
- Immerse yourself in the visual allure of cellular automata in action.

## Instructions

1. Open a terminal or command prompt.
2. Navigate to the program's directory.
3. Run the program using `python conways_game_of_life.py`.
4. Observe the dynamic patterns as they evolve through successive generations.

## Sample Output

```
   O OO      OOO O    O  OOO  O  O   O  O  OO  OO  OO O O   OOOOO   OOO  OOO  O
OOOO O   OO OO  OO O O OOO O  O   OOO O OO   O  O O OOOO O OOOOO OOO  O O O O O
OO OO  OOOOO   OOOOOOO    OO O  O    O   OO O OOO O  O  O  OOO         OOOOO O
OO O O O O  O OO  OOO OOOOO O OO OOO  OO   O  O OOOOO O    OOO  OO   O OO  O  O
  OO   O O   OOO  OO   OO OOO    OOOO  O OOO    OOOO O O       OO O O OO    OO
  OO O OOOOOOO  OO O  OO  O OO   OOOOO        O   O   O OO  OOO  O O    OO OOO
O O O O  OO  OOOOOO OOOO       O OO O O  OOO     O O  OO OOO     OO OOO    O  O
O     OOO  OOOO     O    O OOOOO      OOO  OOO OO  OO OOOOOO  O O  OO   O O  OO
O OO O  OOO   OOO  O O OO O   O OO  O  OO  O    O O OOOO  O    O OO O  O O  O
OO    O       O  O OO OOOOO O OO      O  O OO OO  OOO OO O  OOOOO OOO O  OOOO
O  O OOO O  OO   OOOO O  OOOOO    O OO  O  OOO OOOOOOO  OO     OO OO   OOOO O
       OO OOO  OOO    O O O OO O   O O  OO  OOO   OOOOO  OO  O  O  OO O  O
 OO  O O O    OOOO O  O O     O  O OOO OOOO OOO  O O O  O   O OOO  O O   OOO  O
 OO O OO OOO O    O O OO  OO     OO OOOO  O    O    OOOO  O O O OOOOOO O O OOOO
 OOOOOO O   O O O OOO  O  O   O O OO    O O  OO    O O O OOOO   O  O OOO O   O 
    OO  O OO   OO   O OO      OO O OOO  O OOOOOO   OOOOO OO  O     OOOO
  OOO OOO OO    OO       O  OOO  O       OOO O   O  OOOO O  O OO O O OO   OO  O
  O  O OOOOOO OO  OO OO OOO  O      O  O    OOOO  O OO   O   O O  O  O O O   OO
O  OO  OO O   O  OOO OO O O   O OO    O  O O OOO O    O  OOOO OO O     O  OO
    OOOOOO O O  O      OO OOOOO OO OO  OO O OO O O    OO OOOO O  OOOOOO O  OOO
```