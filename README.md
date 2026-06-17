# ML and EDA Practice Notebooks

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A curated collection of beginner-friendly notebooks for practicing exploratory data analysis, visualization, and introductory machine learning with the Python data science stack.

The repository is organized as a learning portfolio: each notebook focuses on one topic, starts from core concepts, and gradually moves toward simple supervised learning workflows.

## Topics Covered

| Notebook | Focus area |
| --- | --- |
| [`01_numpy.ipynb`](notebooks/01_numpy.ipynb) | NumPy arrays, indexing, slicing, broadcasting, reshaping, and universal functions |
| [`02_pandas.ipynb`](notebooks/02_pandas.ipynb) | Pandas Series, DataFrames, indexing, arithmetic, and dictionary-based data creation |
| [`03_matplotlib.ipynb`](notebooks/03_matplotlib.ipynb) | Line plots, labels, limits, figure/axes objects, subplots, and plot styling |
| [`04_seaborn.ipynb`](notebooks/04_seaborn.ipynb) | Scatter plots, rug plots, distribution plots, KDE plots, and count plots |
| [`05_linear_regression_numpy.ipynb`](notebooks/05_linear_regression_numpy.ipynb) | Polynomial curve fitting with NumPy on an advertising dataset |
| [`06_linear_regression_sklearn.ipynb`](notebooks/06_linear_regression_sklearn.ipynb) | Linear regression with Scikit-learn, train/test split, coefficients, and regression metrics |
| [`07_logistic_regression.ipynb`](notebooks/07_logistic_regression.ipynb) | Logistic regression, sigmoid intuition, classification metrics, and confusion matrix display |

## Repository Structure

```text
.
+-- data/
|   +-- raw/                  # Place local CSV datasets here
+-- notebooks/                # Numbered Jupyter notebooks
+-- .gitattributes            # Keeps notebook diffs readable on GitHub
+-- .gitignore                # Ignores caches, virtual environments, and local data
+-- LICENSE
+-- README.md
+-- requirements.txt
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/AryanAnand-25raj/mL-eda.git
cd mL-eda
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

On Windows:

```bash
.venv\Scripts\activate
```

On macOS/Linux:

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add datasets

Some notebooks use CSV files that are not committed to the repository. Add them locally inside `data/raw/`:

```text
data/raw/
+-- Advertising.csv
+-- dm_office_sales.csv
+-- hearing_test.csv
```

These files are intentionally ignored by Git so local datasets and course files do not get uploaded by accident.

### 5. Start Jupyter

```bash
jupyter lab
```

Open the notebooks from the `notebooks/` directory and run them in order.

## Project Status

This is an educational notebook repository, not a deployed machine learning application. It is best used for:

- revising Python data analysis basics;
- practicing visualization workflows;
- understanding simple regression and classification examples;
- building a foundation for more complete EDA and ML portfolio projects.

## Suggested Next Improvements

- Add markdown explanations before major code sections.
- Add dataset source links and data dictionaries.
- Include evaluation summaries for each model notebook.
- Convert repeated workflows into reusable Python scripts.
- Add a complete end-to-end EDA project using one public dataset.

## License

This project is licensed under the [MIT License](LICENSE).
