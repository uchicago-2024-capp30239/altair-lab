# Altair Lab

For this assignment, you'll be working in a Jupyter notebook.

I've intentionally not given all of the necessary files to run this, instead your first task is to set your repository up as shown below.

Pick either path below, if you already have `poetry` you may use that, otherwise I'd recommend the newer/easier-to-use `uv` that works very similarly.

## `poetry`

0. `cd` into the directory of your repository.

1. Run `poetry init` and answer all questions with default answers/however you see fit.  Don't install any packages at this step.

2. `poetry add jupyter`

3. `poetry run jupyter lab` will run Jupyter, open your browser, and you can browse to the .ipynb file that you need to edit.  That file contains all instructions.

4. Install other libraries you will use: `poetry add altair` and `poetry add pandas` or `poetry add polars`

5. Be sure to check in the created `pyproject.toml`/`poetry.lock` files.

## `uv`

0. `cd` into the directory of your repository.

1. `uv init`

2. `uv add jupyter`

3. `uv run jupyter lab` will run Jupyter, open your browser, and you can browse to the .ipynb file that you need to edit.  That file contains all instructions.

4. Install other libraries you will use: `uv add altair` and `uv add pandas` or `uv add polars`

5. Be sure to check in the created `pyproject.toml`/`uv.lock` files.

## Submission

When you are done, ensure that your notebook is clean & readable.

- Move any scratch code to another file or to the bottom and clearly mark it as such.
- 'Kernel -> Restart Kernel and Run All' to ensure that your notebook executes in the order it is written.


You may also try this to clean up your code automatically:

- First **check in your work** make a commit before running this command, just in case.
- `uv add ruff`/`poetry add ruff`
- `ruff format altair_lab.ipynb`

Once satisfied, commit and submit your repository on Gradescope.

There are no autograder tests.
