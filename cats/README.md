# Cats Typing Test

A typing-speed project from the CS 61A course structure. The project focuses on text selection, typing accuracy, words-per-minute calculation, autocorrect, edit distance, multiplayer progress reporting, and fastest-word analysis.

## Main Files

| Path | Purpose |
| --- | --- |
| `cats.py` | Main implementation for paragraph selection, accuracy/WPM, autocorrect, edit distance, multiplayer progress, and command-line typing test. |
| `cats_gui.py` | Local web server and route handlers for the typing GUI. |
| `utils.py` | String and keyboard-distance helpers used by the project. |
| `data/` | Paragraph and word-list data used by the typing test and autocorrect. |
| `tests/` | Project tests from the original scaffold. |
| `gui_files/`, `images/`, `favicons/`, `multiplayer/` | Provided GUI, assets, and multiplayer support code. |

## Run

Command-line typing test:

```bash
python3 cats.py -t
```

GUI:

```bash
python3 cats_gui.py
```

## Notes

- `enable_multiplayer` is set to `False` in `cats.py`.
- `final_diff` is still the optional extension placeholder; the working autocorrect path uses `minimum_mewtations` and `feline_flips`.
- Generated `__pycache__` files are still present from the original upload and should be removed in a later cleanup commit after verification.
