# 🧨 MineHunter

**Version:** 1.0.0  
_A simple Minesweeper game built with Unity._

---

## 🎮 Features
- Automatically generates a minefield.
- Left-click to reveal blocks.
- Right-click to flag suspected mines.
- Game over when a mine is clicked.
- Shows a restart button to manually reset the game after failure or win.
- Displays game over or victory message.

---

## ⚠️ Limitations
- ❌ No screen size adaptation (fixed grid size).
- ❌ Restart does **not** automatically reset the whole scene (manual button reset only).
- ❌ No difficulty selection (fixed mine count and grid size).

---

## 🛠️ How to Play
1. Open the project in **Unity**.
2. Press `Play` to start.
3. Left-click on the blocks to reveal.
4. Right-click to place flags.
5. If you click on a mine, the game will show **Game Over** and reveal all mines.
6. Press the **Restart** button to reset and start a new game.

---

## 🗂️ Project Structure
| Folder / File            | Description              |
|--------------------------|--------------------------|
| `MineGridManager.cs`     | Core grid and game logic |
| `MineButton.cs`          | Single block behavior    |
| `MineField (Canvas)`     | Grid container           |
| `MineButton (Prefab)`    | Block prefab             |
| `GameOverText (TMP)`     | Game over message        |
| `RestartButton (Button)` | Restart the game         |

---

## 🚀 Future Improvements
- Adaptive grid layout.
- Dynamic difficulty levels.
- Timer and scoring system.
- Auto-restart on win or loss.

---

## 📌 Version Log

| Version | Date       | Description         |
|---------|------------|---------------------|
| 1.0.0   | 2025-03-05 | Initial release 🎉 |
