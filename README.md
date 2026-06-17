# ML & Data Science Practice Notebooks

A set of practice notebooks covering the core Python data science stack — NumPy, Pandas, Matplotlib, Seaborn, and basic supervised learning with Scikit-learn. This is learning material, not a finished analysis or production project.

## What's actually in here

| Notebook | Topics covered |
|---|---|
| `ADVANCE_PYTHON(NUMPY).ipynb` | Array creation, indexing, slicing, boolean masking, broadcasting, universal functions (sqrt, exp, log, trig), reshaping |
| `ADVANCE_PYTHON{PANDAS}.ipynb` | Series and DataFrame basics, indexing, arithmetic on Series, dictionaries to Series |
| `ADVANCE_PYTHON[MATPLOTLIB].ipynb` | Basic line plots, labeling/limits, figure/axes objects, subplots, styling (color, linewidth, linestyle) |
| `ADVANCE_PYTHON[SEABORN].ipynb` | Scatter plots, rug plots, distribution plots (`displot`, `kdeplot`), count plots on a sales dataset |
| `ADVANCE_PYTHON[LINEAR_REGRESSION].ipynb` | Manual polynomial curve fitting with `np.polyfit` on an advertising dataset, comparing degree 1–3 fits |
| `ADVANCE_PYTHON[SKITLEARN].ipynb` | Linear regression using `sklearn.linear_model.LinearRegression`, train/test split, coefficient inspection |
| `ADVANCE_PYTHON[LOGISTIC_REGRESSION].ipynb` | Logistic regression on a hearing-test dataset, sigmoid function, train/test split, prediction |

There is no exploratory data analysis project here despite the repo name — these are sequential tutorial-style exercises with no markdown explanations. Each notebook is essentially "import library → run a series of commands."

## Known issues (read before you try to run anything)

- **Datasets are not included.** Notebooks reference `Advertising.csv`, `hearing_test.csv`, and `dm_office_sales.csv`, but none of these files are in the repo.
- **File paths are hardcoded to a local Windows machine** (e.g. `C:\Users\ASUS\OneDrive\Documents\Desktop\datasets_python\...`). Nothing will run as-is on another computer.
- **No `requirements.txt`.** Library versions used (numpy, pandas, matplotlib, seaborn, scikit-learn) are not pinned.
- **No model evaluation in most cases** — predictions are generated but accuracy/error metrics are largely not computed or shown.
- One filename has a typo: `ADVANCE_PYTHON[SKITLEARN].ipynb` should be `SKLEARN`.

## To actually run these

1. Clone the repo.
2. Install dependencies: `pip install numpy pandas matplotlib seaborn scikit-learn jupyter`
3. Source your own copies of `Advertising.csv`, `hearing_test.csv`, and `dm_office_sales.csv` (these are common files from intro ML courses, e.g. Pierian Data's Python for Data Science course).
4. Replace the hardcoded file paths in each notebook with wherever you put those CSVs.
5. Run with Jupyter Notebook or JupyterLab.

## Why this repo exists

This is a personal practice log while learning the data science / ML stack — not a portfolio-ready analysis project. If you're looking for applied EDA or ML work, this isn't it yet.
