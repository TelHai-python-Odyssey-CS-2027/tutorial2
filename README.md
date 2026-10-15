# Tutorial 2 — Scalars and functions

Practice for lecture 2. Open the notebooks and run the cells.

**Colab from GitHub:** a normal click stays in the same tab (GitHub removes “open in new tab”). Use **Ctrl+click** (Windows/Linux) or **⌘+click** (Mac), or middle-click, to open Colab in a new tab.

- <a href="https://colab.research.google.com/github/TelHai-python-Odyssey-CS-2027/tutorial2/blob/main/scalars.ipynb" target="_blank" rel="noopener noreferrer"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Scalars"/></a> `scalars.ipynb`
- <a href="https://colab.research.google.com/github/TelHai-python-Odyssey-CS-2027/tutorial2/blob/main/function_condition.ipynb" target="_blank" rel="noopener noreferrer"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Functions & conditions"/></a> `function_condition.ipynb`

Optional (after you try): <a href="https://colab.research.google.com/github/TelHai-python-Odyssey-CS-2027/tutorial2/blob/main/function_condition_solution.ipynb" target="_blank" rel="noopener noreferrer"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Solution"/></a> `function_condition_solution.ipynb`

## How to work

1. Open a notebook in Colab (buttons above; prefer Ctrl/⌘+click) or locally.
2. Run the cells and experiment.

## `math_utils.py` — graded in this tutorial

Implement **only** `find_max_number(num1, num2, num3)` in `math_utils.py` (return the largest of the three numbers, including when two values are tied).

Commit to run autograding (10 cases, 1 point each: each position, negatives, floats, all equal, several ties). A failing case shows the input, expected value and a hint in the autograding **Details**. Watch for ties such as `(3, 3, 1)` — using strict `>` can fail those cases.

`function_condition.ipynb` has a **self-check** cell that runs the same cases — run it before you copy your function into `math_utils.py`.

The homework (**PS2**) builds on this file: there you will also implement `find_mean` and `find_mean_std`.

## Optional: keep your changes in Google Drive

In Colab: **File → Save a copy in Drive**.
