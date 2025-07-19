 # README

This is a project looking at global tertiary education using the Barro-Lee dataset. It currently has two Jupyter notebooks:

## Project Files
1. **01_explore_barro_lee.ipynb** - Loads the raw Barro-Lee data, peeks at rows/columns, checks missing values, basic cleaning/reformatting.
2. **02_analysis_trends.ipynb** - Works off the cleaned data to look at overall tertiary education trends, annual changes, regional comparisons, with written analyses of the graphs.

## Requirements
- Python 3.x
- Jupyter Notebook (or JupyterLab)
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `random`

## How to Run
1. Open `01_explore_barro_lee.ipynb` and run all cells.
2. Open `02_analysis_trends.ipynb` and run all cells.

## Data Source
Barro & Lee Educational Attainment Dataset (public academic dataset of education by country & year). Currently using data with:
- Ages 25-65
- Country & region specified
- Country population
- No gender distinction