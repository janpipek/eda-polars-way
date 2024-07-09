# eda-polars-way

Tutorial: Exploratory Data Analysis, the Polars Way

(as given at [PyCon Italia 2024](https://2024.pycon.it/) and [EuroPython 2024](https://ep2024.europython.eu/)).

## Preparation

Please prepare a Python environment that you can use during the workshop.
We will work in Jupyter Notebook. However, you can also use jupyter lab or one of the IDES,
[Visual Studio Code](https://code.visualstudio.com) or [PyCharm](https://www.jetbrains.com/pycharm/).

### Clone this repository

```bash
git clone https://github.com/janpipek/eda-polars-way.git
```

or using `gh` client:

```bash
gh repo clone janpipek/eda-polars-way
```

Alternatively, you can just download the repo as a package from here:

https://github.com/janpipek/eda-polars-way/archive/refs/heads/main.zip

### Prepare Python Environment

The included `requirements.txt` file should be enough for you to create a Python environment
using the `pip` command.

Python version 3.10+ is required.

First, `cd` into the repository directory:

```bash
cd eda-polars-way
```

#### Pip/uv installation

```bash
# Activate the environment (every time you open the shell)
python -m venv .venv         # (or `uv venv`)
source .venv/bin/activate    # Linux, Mac
.venv\Scripts\activate.bat   # Windows

# Install the required packages (once)
python -m pip install -r requirements.txt  (or `uv pip install -r requirements.txt`)
```

(note that we require the new, stable 1.0 version of polars)

### (Absolutely lazy) on-line environment

This is not recommended but working in case you have probelms installing on your laptop.

Create an account at https://deepnote.com (for free) and launch the repo by clicking the button:

[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?url=https%3A%2F%2Fgithub.com%2Fjanpipek%2Feda-polars-way)

Note that you will have to install additional packages (there is a command you need to uncomment).

## How to use this repo

All contents (a bit of text + all exercises) are located in `exercises.ipynb`. The exercise are partly filled and accompanied by hints. If you are still unsure, in `solutions.ipynb`, you have working code to answer the questions. To help SQL-savvy, the `solutions-sql.ipynb` file contains solution using the SQL API of polars).

## Data sources

All the data sources are believed to be open and publicly distributable, 
see `data/README.md` for more details.

## Useful links

### Official documentation

- [Polars User Guide](https://docs.pola.rs/)
- [Polars API reference](https://docs.pola.rs/py-polars/html/reference/index.html)

### Articles

- [Python Polars: A Lightning-Fast DataFrame Library](https://realpython.com/polars-python/) @ RealPython

### Talks & videos

- [R. Vink: What polars does for you](https://www.youtube.com/watch?v=UwRlFtSd_-8), EuroPython 2023
- [M. Harrison: Getting Started with Polars](https://www.youtube.com/watch?v=CJ0f45evuME), Pycon US 2023

### On-line courses

- https://www.udemy.com/course/data-analysis-with-polars/
