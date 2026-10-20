# ✊✋✌️ Rock Paper Scissors — 3 Python Versions

Three simple Python implementations of the classic Rock-Paper-Scissors game, from one-shot to replayable to scored.

## Versions

| Version | File | Description |
|---|---|---|
| 1. One Level | `Rock Paper Scissor Game(One Level).ipynb` | Single round, text input (`rock/paper/scissors`), instant win/lose/tie result. Best for beginners. |
| 2. Replayable | `Rock Paper Scissor Game.ipynb` | Infinite loop with rules display, numeric menu (1-3), `Y/N` replay prompt. No ties — computer re-rolls on tie. |
| 3. With Rating | `Rock Paper Scissor Game(With Rating).ipynb` | Score system (`userRate` vs `sysRate`), continuous play, exit with `4`, final result: Won/Los/Equal. |

> ⚠️ Note: Version 3 currently has an `IndentationError` on line 10 — fix indentation before running.

## How to Run

```bash
jupyter notebook
# open any .ipynb file and run the cell
# or convert to .py:
jupyter nbconvert --to script "Rock Paper Scissor Game(One Level).ipynb"
python "Rock Paper Scissor Game(One Level).py"
```

## Rules

- Rock > Scissors
- Scissors > Paper
- Paper > Rock

## 💬 Which version do you prefer?

1, 2, or 3 — and why?

**Contribute:** Suggest a **hybrid version** combining the best of all three — e.g. text + numeric input, replay option, scoreboard, tie handling, and input validation. Open a PR / Issue with your idea! 🚀
