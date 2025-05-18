# python_games
# 🎲 Snake and Ladder Game - Windows EXE

This is a Windows `.exe` version of the classic **Snake and Ladder** game, originally written in Python.

---

## 📦 How to Use

1. **Download** the `.exe` file:
   - 👉 `SnakeAndLadder.exe` (link or path here)

2. **Double-click** to run the game.
   - No need to install Python or any dependencies.

3. Play in the terminal:
   - Roll the dice
   - Avoid snakes 🐍
   - Climb ladders 🪜
   - Try to reach position 100

---

## 🎯 Features

- CLI game (text-based)
- Start only on rolling 6 🎯
- Snakes that send you backwards
- Ladders that boost you forward
- Colored terminal output (red/green highlights)
- Auto-replay option when you win

---

## 🖥 System Requirements

- Windows 10/11
- No Python installation needed

---

## ⚠️ Notes

- This is a console-based game. The terminal will open when the game starts.
- If your antivirus flags it, it’s a **false positive** — it was created using `pyinstaller` from a clean Python script.

---

## 🔧 Developer Instructions

If you're a developer and want to build the `.exe` yourself:

```bash
pip install pyinstaller
pyinstaller --onefile snake_and_ladder.py
