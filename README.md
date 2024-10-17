# Sudoku Game

## Overview
This Python-based Sudoku game provides a graphical interface using Pygame. Users can solve the Sudoku puzzle manually or allow the computer to solve it. The interface supports selecting cells, entering numbers, and validating the s
## Features
- Interactive GUI for playing Sudoku
- Manual entry of numbers
- Automatic solving of the Sudoku puzzle
- Highlighting of selected cells and incorrect placements

## Requirements
- Python 3.x
- Pygame

## Installation
1. Ensure you have Python 3.x installed on your system.
2. Install Pygame using pip:
    ```sh
    pip install pygame
    ```
3. Download or clone the Sudoku script to your local machine.

## How to Use
1. Open your terminal or command prompt.
2. Navigate to the directory where the script is located.
3. Run the script using Python:
    ```sh
    python sudoku.py
    ```

## Gameplay Instructions
- **Select a Cell:** Click on a cell to select it.
- **Enter a Number:** Use the number keys (1-9) to enter a number into the selected cell.
- **Temporary Number:** Sketch a temporary number by selecting a cell and pressing a number key.
- **Confirm Entry:** Press the Enter key to confirm the number in the selected cell.
- **Clear Cell:** Press the Delete key to clear the selected cell.
- **Solve Automatically:** Press the Spacebar to let the computer solve the Sudoku puzzle.
- **Exit:** Close the window to exit the game.

## Commands
### Mouse Click
- Click on a cell to select it. The selected cell is highlighted in red.

### Number Keys (1-9)
- Enter a number into the selected cell as a temporary sketch.

### Enter Key
- Confirm the number in the selected cell.

### Delete Key
- Clear the selected cell if it contains a temporary number.

### Spacebar
- Automatically solve the Sudoku puzzle using a graphical solving method.

## Game Outputs:

![image](https://github.com/SaadARazzaq/Sudoku-Game/assets/123338307/1274c722-a724-45be-bf0a-f736f062c3ad)
![image](https://github.com/SaadARazzaq/Sudoku-Game/assets/123338307/33d6db38-65bf-431f-969a-03feee59c20a)
![image](https://github.com/SaadARazzaq/Sudoku-Game/assets/123338307/8d4737ca-8df6-423b-80cf-3d7a2bc77c1b)
![image](https://github.com/SaadARazzaq/Sudoku-Game/assets/123338307/cf5753c0-10a1-485d-8fca-cf217d6c5679)

## Test Cases:

![image](https://github.com/SaadARazzaq/Sudoku-Game/assets/123338307/ce59f9d4-313d-45b9-9b57-731623ff786d)
![image](https://github.com/SaadARazzaq/Sudoku-Game/assets/123338307/72e8c426-1dd6-4ae3-bb02-aba658677e6c)

## Developer Notes
- The Sudoku game uses Pygame for rendering the graphical interface and handling user input.
- The `Grid` class represents the Sudoku board and contains methods for drawing, selecting, and solving the puzzle.
- The `Cube` class represents individual cells in the Sudoku grid, with methods for drawing the cell and handling temporary and permanent values.
- The `solve` and `solve_gui` methods implement the backtracking algorithm to solve the puzzle.
- The `find_empty` method uses a heuristic to find the cell with the fewest possible values for efficient solving.

## Future Enhancements
- Add more Sudoku puzzles with varying difficulty levels.
- Implement a hint system to assist players.
- Add an option to highlight incorrect placements automatically.
- Improve the graphical interface with better visual feedback.

---

Enjoy playing the Sudoku game! If you encounter any issues or have suggestions for improvements, feel free to contribute or open an issue.
