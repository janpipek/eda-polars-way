# eda-polars-way

Tutorial: Exploratory Data Analysis, the Polars Way

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

### Prepare Python Environment

The included `requirements.txt` file should be enough for you to create a Python environment
using the `pip` command.

Python version 3.10+ is required.

First, `cd` into the repository directory:

```bash
cd eda-polars-way
```

#### Pip installation

```bash
# Activate the environment (every time you open the shell)
python -m venv .venv
source .venv/bin/activate    # Linux, Mac
.venv\Scripts\activate.bat   # Windows

# Install the required packages (once)
python -m pip install -r requirements.txt
```

## Data sources

All the data sources are believed to be open and publicly distributable, 
see `data/README.md` for more details.

## Useful links

### Official documentation

- [Polars API reference](https://docs.pola.rs/py-polars/html/reference/index.html)

### Articles

- [Python Polars: A Lightning-Fast DataFrame Library](https://realpython.com/polars-python/) @ RealPython

### Talks & videos

-  https://janpipek.github.io/talks/prague-python-pizza_2024/slides.pdf

### On-line courses