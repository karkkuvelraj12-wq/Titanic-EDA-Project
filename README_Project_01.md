# Project 01 — Exploratory Data Analysis (EDA) on Titanic

## Objective
Use Pandas to inspect and clean the Titanic dataset, then compare survival rates by sex, passenger class, and age band.

## Questions
1. Did survival rates differ between female and male passengers?
2. Did passenger class relate to survival rate?
3. How did survival rates vary across age bands?

## Tools
- Python 3.10+
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook or Google Colab

## How to run
1. Open `Project_01_Titanic_EDA.ipynb` in Jupyter or upload it to Google Colab.
2. Install dependencies if needed: `pip install pandas numpy matplotlib seaborn jupyter`
3. Run all cells from top to bottom. The first dataset load may require an internet connection.
4. Use the numeric findings printed near the end of the notebook to write your final three-point summary.

## Cleaning choices
- Missing ages are filled with the median age for the same passenger class and sex.
- Missing embarkation values are filled with the most frequent category.
- `deck` is dropped because it has substantial missingness.
- Duplicate rows are counted and reported rather than automatically removed.

## Submission
Submit the notebook link with access enabled, or export it as HTML/PDF if your task portal accepts that format. Verify every cell runs before submitting.
