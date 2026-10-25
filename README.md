# func-python

Notes and experiments on how Python really works under the hood, building
toward a solid grasp of functional programming in Python 3.13. Written as
part of a deliberate effort to deepen my fundamentals alongside my work as
a Python backend developer.

## What this repo is
- Jupyter notebooks I work through and annotate myself, one concept per notebook
- Each notebook pairs short explanations with runnable code I can poke at
- Topics are studied in order: the memory model first, then function
  parameters, then functions as objects, closures, `functools`, `itertools`
- The focus is on knowing *when* an FP pattern helps, not using it everywhere

## What's inside
| Area | Notebooks |
|------|-----------|
| Variables & memory | References, reference counting, garbage collection, mutability, shared references, equality, interning, peephole optimisations |
| Function parameters | Positional & keyword args, unpacking and extended unpacking, `*args` / `**kwargs`, a simple function timer, mutable-default pitfalls |
| Parameter extras | Sentinel values for defaults, naming `*args` / `**kwargs` deliberately |

Notebooks live in [`fred_tut/`](fred_tut/). See [PROGRESS.md](PROGRESS.md) for
what's done and what's next.

## Running locally
    python -m venv .venv
    .venv\Scripts\activate          # Windows  (source .venv/bin/activate on macOS/Linux)
    pip install -r requirements.txt

Then open any notebook in VS Code (or Jupyter) and pick the `.venv` kernel.

## Why it exists
Real backend work (Django, FastAPI, PostgreSQL) rewards knowing what happens
under the hood: why a mutable default argument leaks state between requests,
why two names can point at the same object, why a pure function is trivially
testable and cacheable. This repo is where I build that intuition, one
notebook at a time.
