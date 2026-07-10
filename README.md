# Projects

This repository is an older archive of small Python projects, class projects, and practice work. I keep it organized here so I can come back to the code, remember what each project was for, and show representative work without losing the original context.

## Contents

| Folder | Project | What it shows |
| --- | --- | --- |
| `PIL Image/` | ASCII image converter | Basic image processing with Pillow, command-line input, and text output. |
| `cats/` | Typing test project | String processing, accuracy/WPM calculations, autocorrect, recursion/edit distance, and multiplayer progress logic inside a provided CS 61A project scaffold. |
| `hog/` | Game of Hog project | Game simulation, dice rules, commentary functions, strategy evaluation, and GUI/server integration inside a provided CS 61A project scaffold. |

## Running The Projects

### ASCII Image Converter

```bash
cd "PIL Image"
python3 "from PIL import Image.py" path/to/image.jpg
```

The script prints an ASCII version of the image and writes it to `img.txt`.

### Cats Typing Test

```bash
cd cats
python3 cats.py -t
```

The GUI version can be started with:

```bash
python3 cats_gui.py
```

### Hog

```bash
cd hog
python3 hog.py --run_experiments
```

The GUI version can be started with:

```bash
python3 hog_gui.py
```

## Notes

- The `cats` and `hog` folders include starter files, tests, GUI assets, and data files from the original course project structure. The main implementation work is in `cats/cats.py` and `hog/hog.py`.
- Some generated files from the original upload are still present, including `__pycache__` folders and compiled Python files. They are now ignored by `.gitignore`; removing the already committed copies is a separate cleanup step.
- The next pass should rename the ASCII image script to a clearer filename, add a small dependency file for Pillow, and remove generated cache files after verifying the projects still run.
