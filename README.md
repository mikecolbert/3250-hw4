# Homework 4

## NHL project

Scraping and joining data.

- task 1
- task 2

[ ] task 1  
[x] task 2  
[ ] task 3

&#128640;

  Repository
    ├── README  
    ├── Other  
    ├──  data  
    │    ├──  test  
    │    └──  test2  


├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Additional documentation for this project beyond the top-level README.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│   └── .ipynb            the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── pyproject.toml     <- The Python requirements and development experience configuration file
│
├── Cargo.toml         <- The Rust configuration file
│
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── modules        <- Python scripts for this project separated by functional units
│   │   └── .py
│   ├── tests          <- Pytest scripts for this project
│   │   └── .py
│   └── lib.rs         <- Rust code that can be compiled and called from Python with pyo3
│                         and maturin, by running the command 'maturin develop'
├── lint.sh            <- Run mypy and ruff on the python code
└── venv.sh            <- Generate a virtual environment and install dependencies
