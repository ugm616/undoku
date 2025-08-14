# UnDoku

---

## About the Puzzle

UnDoku was created to blend the clean, logical purity of classic Sudoku with the directional clue logic found in certain sum‑based puzzles. The aim is to offer a challenge that is **minimalist in presentation** yet **rich in deduction**, where every clue is purposeful and the path to the solution is human‑solvable without guessing. Directional arrow clues provide immediate visual context, encouraging solvers to think spatially as well as numerically.  

Whether you are a casual player or a seasoned logic enthusiast, UnDoku rewards both methodical reasoning and creative leaps.

---

**UnDoku** is a web‑based logic puzzle game inspired by Sudoku — but with a twist.

In UnDoku, you still need to place each digit exactly once per row and column, but directional sum clues add an extra layer of challenge. Tiny arrow‑boxes in the grid point in a direction; the number shown equals the sum of all digits along that ray (excluding the clue cell itself).

---

## Goal

Fill the grid so that:

- Every row contains all numbers from `1` to `N` exactly once.
- Every column contains all numbers from `1` to `N` exactly once.
- Clues are satisfied:  
  - Each arrow points to a set of cells in a straight line.  
  - The clue’s number is the sum of the digits in those cells.

---

## How to Play

1. Select a cell by clicking it or using the arrow keys.
2. Enter a digit:
   - Click a number on the keypad or press a number key on your keyboard.
3. Pencilmarks (candidates):
   - Shift + number or enable the Pencil toggle to add/remove small candidate numbers in a cell.
   - Clear candidates with Shift + Clear or when placing a main digit.
4. Clear a cell:
   - Press `0`, `Delete`, or `Backspace` (without Pencil mode) or click Clear on the keypad.
5. Hints:
   - Click Hint to auto‑fill a safe step.
6. Check:
   - Click Check to highlight any conflicts or violated clues.
7. Reveal:
   - Click Reveal to fill in the solution (ends the puzzle).
8. New game:
   - Choose a grid size and difficulty, then click New.

---

## Pencilmarks

Pencilmarks are small numbers shown inside a cell to note possible values:
- Toggle Pencil mode with the Pencil button next to the keypad.
- In Pencil mode (or holding Shift), clicking or pressing a number will toggle it in the selected cell.
- They disappear automatically when you enter a final answer in that cell.

---

## Strategy Tips

- Start with easy eliminations using row and column logic.
- Use directional sum clues to deduce unique possibilities.
- Pencilmarks help track candidates and avoid guesswork.
- Check regularly to catch mistakes early.

---

## Winning

When every cell is correctly filled and all clues are satisfied, a celebratory modal will appear to confirm your success.

---

## Running Locally

   Clone this repository:
   ```bash
   git clone https://github.com/yourusername/undoku.git
   cd undoku
   Open index.html (or rabs_puzzle.html) in your browser.
   No build steps, no dependencies — just open and play.
