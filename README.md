# CS 61A Coursework Archive

This repository is my archive for CS 61A work. I keep it around as a reference for the main ideas from the course: Python fundamentals, recursion, higher-order functions, object-oriented programming, interpreters, Scheme, and SQL.

## Contents

- `project/hog` - simulator and strategy work for the Hog dice game.
- `project/cats` - typing test project with autocorrect and multiplayer timing.
- `project/ants` - Ants vs. SomeBees tower-defense simulation.
- `project/scheme` - Scheme interpreter project.
- `hw` - homework exercises from the course.
- `lab` - lab exercises and smaller practice problems.
My local course folder also has old review PDFs, but I keep the public repo focused on code and project files.

## Running The Code

Most assignments were originally distributed with the CS 61A OK autograder. I intentionally did not commit the repeated `ok` executable or personal `.ok_*` state files, because they made the repository much larger and were not part of my actual source work.

When I want to run an assignment locally, I use a fresh OK copy from the course distribution and run it from that assignment folder, for example:

```bash
cd project/cats
python3 ok --local
```

For regular Python files, I also use the doctests in the files when they are available:

```bash
python3 -m doctest -v project/cats/cats.py
```

## Notes

This is a course archive, not a polished package. Some folders are complete enough to revisit directly, while some still contain starter markers from the original course files. I kept those visible instead of filling in old coursework after the fact, so the repo stays honest about what I actually had saved.
