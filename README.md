# Task 03 — Sudoku Solver

An interactive web-based Sudoku solver that takes an input grid representing an unsolved Sudoku puzzle and automatically fills in the missing numbers using a backtracking algorithm.

---

## 🧩 Features

- Automatically solves any valid Sudoku puzzle using backtracking
- 3 built-in difficulty levels — Easy, Medium, Hard
- Click any empty cell and enter numbers manually using the on-screen number pad
- Keyboard support — type numbers and navigate with arrow keys
- Solved numbers shown in blue to distinguish from given numbers
- Highlights matching numbers when a cell is selected
- Clear button resets only the auto-solved cells
- New Puzzle button loads a fresh puzzle

---

## 🌐 Live Demo
👉 [Click here to try the Sudoku Solver](https://your-username.github.io/your-repo-name/sudoku_solver.html)

---

## 🚀 How to Run

1. Download or clone this repository
2. Open `sudoku_solver.html` in any web browser
3. No installation or internet connection required

---

## 📁 File Structure

```
Task-03-Sudoku-Solver/
├── sudoku_solver.html    → Full app (HTML + CSS + JS)
└── README.md             → Project documentation
```

---

## 🎮 How to Use

1. Select a difficulty level from the dropdown (Easy / Medium / Hard)
2. A pre-loaded puzzle will appear on the grid
3. Optionally enter your own puzzle by clicking a cell and using the number pad
4. Click **Solve** to automatically solve the puzzle
5. Click **Clear** to reset solver-filled cells
6. Click **New Puzzle** to load a fresh puzzle

---

## ⚙️ Algorithm — Backtracking

The solver uses a **backtracking algorithm**, which works as follows:

```
1. Find the first empty cell in the grid
2. Try placing numbers 1–9 in that cell
3. Check if the number is valid:
   - Not already in the same row
   - Not already in the same column
   - Not already in the same 3×3 box
4. If valid → move to the next empty cell and repeat
5. If no number works → backtrack to the previous cell and try the next number
6. Repeat until all cells are filled (solved) or no solution exists
```

### Time Complexity
- Worst case: O(9^m) where m = number of empty cells
- In practice, much faster due to constraint checking

---

## 🛠️ Technologies Used

- **HTML5** — Page structure and grid layout
- **CSS3** — Styling, dark theme, grid visual separation
- **JavaScript (Vanilla)** — Backtracking solver, DOM manipulation, keyboard navigation

---

## 👨‍💻 Internship

**Organization:** SkillCraft Technology  
**Task:** 03 — Sudoku Solver  
**Intern:** [Your Name]
