# Interactive 8-Queens Chessboard (Smalltalk - Squeak)

## Overview
This project is an **interactive chessboard** implementation in **Smalltalk (Squeak)** for solving the **8-Queens problem**. The program visualize the 8-queens solution, allows users to block cells using right-click (add conditions) on the board, and highlights conflicts dynamically.

## Features
- **Graphical Interface (Morphic):** Clickable chessboard for interactive cell blocking.
- **Algorithmic Conflict Detection:** Highlights conflicting queens in real time.
- **Object-Oriented Design:** Board, squares, and queens are managed as independent objects.
- **Solution Visualization:** Displays correct configurations and iterates through multiple solutions.
- **Right-Click Blocking:** Prevents placement in certain squares to explore constrained setups.

## How to Run
### Prerequisites
- Ensure that the file **`queen.png`** is located in the **`resources`** folder.

### Running the Program
1. Open the project in **Squeak Smalltalk**.
2. Open a **Workspace** in Squeak.
3. Enter the following command:
   ```smalltalk
   (Interactive8Queens new) solve.
   ```
4. Execute the command to start the interactive 8-Queens solver.

## Technologies Used
- **Language:** Smalltalk (Squeak)
- **GUI Framework:** Morphic
- **Algorithm:** Backtracking for solution validation

## Future Improvements
- Enhance UI for a more intuitive user experience.
- Add a reset button to clear the board easily.

## Credits
Developed by Inbar Hecht as a learning project in Smalltalk (Squeak).

