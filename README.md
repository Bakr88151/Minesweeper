# Minesweeper with Pygame

This Minesweeper project is implemented using the Pygame library. It includes both the game logic (`minesweeper.py`) and the graphical user interface (`runner.py`). The Minesweeper game allows players to reveal cells, mark mines with flags, and win by uncovering all safe cells.

## Installation

Before running the project, make sure you have Python and Pygame installed:

```bash
pip install pygame
```

## How to Play

1. Run `runner.py` to start the game.
2. Click a cell to reveal it.
3. Right-click a cell to mark it as a mine.
4. Mark all mines successfully to win!

## Game Features

### Game Logic (`minesweeper.py`)

- The Minesweeper class handles the game logic, including mine placement, board initialization, and tracking discovered mines.
- The AI logic is implemented in the MinesweeperAI class, allowing the AI to make safe or random moves.
- The project includes a basic graphical representation of the Minesweeper board.

### Graphical User Interface (`runner.py`)

- The GUI is built using Pygame to provide a visual Minesweeper experience.
- Players can interact with the game by clicking cells to reveal them or right-clicking to mark mines with flags.
- An AI Move button allows the AI to make moves automatically based on its knowledge.
- A Reset button allows the player to start a new game.

## Project Structure

- `minesweeper.py`: Contains the Minesweeper and MinesweeperAI classes.
- `runner.py`: Implements the Pygame GUI for Minesweeper.
- `assets/`: Directory containing fonts and images used in the GUI.

## Acknowledgments

This project was created for educational purposes and is based on the classic Minesweeper game.

Feel free to explore the code, make improvements, or customize the game further!
