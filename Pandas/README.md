<h1 align="center">Pandas Tutorial Notebook</h1>
<p align="center"><img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Pandas-Latest-150458?logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/NumPy-Latest-013243?logo=numpy&logoColor=white" alt="NumPy"> <img src="https://img.shields.io/badge/Matplotlib-Latest-11557c?logo=python&logoColor=white" alt="Matplotlib"> <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" alt="Jupyter"></p>
<p align="center">A hands-on guide to core Pandas concepts for data manipulation, cleaning, and transformation workflows.</p>

---

## Contents

- **Boolean Masking** — Filtering data with conditional expressions
- **`value_counts()`** — Frequency distribution in categorical data
- **Plotting in Pandas** — Built-in visualization directly from DataFrames

## Dataset

The notebook uses `matches.csv`. Ensure this file is in the same directory as the notebook.

```python
import pandas as pd
df = pd.read_csv('matches.csv')
```

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib (for plots)

```bash
pip install pandas numpy matplotlib jupyter
```
