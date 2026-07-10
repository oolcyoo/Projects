# Hog Game

A dice-game simulation project from the CS 61A course structure. The project implements the core game rules, score commentary, strategy helpers, and experiment runner for evaluating strategies.

## Main Files

| Path | Purpose |
| --- | --- |
| `hog.py` | Main game logic: dice rolling, turn scoring, game loop, commentary functions, strategy helpers, and experiments. |
| `dice.py` | Dice utilities, including fair dice and deterministic test dice. |
| `hog_gui.py` | Local web server and route handlers for the Hog GUI. |
| `calc.py` | Strategy comparison helper that talks to the original course service. |
| `default_graphics.py`, `gui_files/` | Provided GUI graphics and frontend support files. |
| `tests/` | Project tests from the original scaffold. |

## Run

Run strategy experiments:

```bash
python3 hog.py --run_experiments
```

Start the GUI:

```bash
python3 hog_gui.py
```

## Notes

- `final_strategy` is still a simple baseline that returns `6`; the stronger strategy work is in `picky_piggy_strategy` and `hog_pile_strategy`.
- `calc.py` depends on the original course authentication/service flow and may not be useful outside that context.
- Generated `__pycache__` files are still present from the original upload and should be removed in a later cleanup commit after verification.
