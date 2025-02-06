# Minesweeper

Minesweeper is a logic puzzle video game. It features a grid of clickable tiles, with hidden "mines" (depicted as naval mines in the original game) scattered throughout the board. The objective is to clear the board without detonating any mines, with help from clues about the number of neighboring mines in each field.

## **How Minesweeper Works:**
### I. Rules of the Game:
1. **Grid & Mines:** The game board consists of a grid (10x10 in this case) with a set number of hidden mines (10 mines per board).
2. **Selecting Tiles:**
   - Selecting a tile reveals either a number or a mine
   - Numbers indicate how many mines are adjacent to that tile
   - If you land on a mine, you lose the game
3. **Using Logic & Flags:**
   - You can place **flags** on suspected mine locations [*]
   - You can use the numbered tiles to deduce where mines are
   - Revealing all non-mine tiles wins the game

---
   
### II. Game Mechanics:
- The first click is always safe [*]
- If a tile has no adjacent mines (0), it reveals surrounding tiles automatically 
- Placement of flags [*]
- Winning Condition: Uncover all non-mine tiles

---

> A star signifies that the feature is yet to be implemented in this repository.
