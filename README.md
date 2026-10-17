# COVID-19 Global Data Analysis

Python notebook that prepares a global COVID-19 time-series dataset (CSV, 187 countries)
and visualises case trends per country and worldwide.

## Steps
- Load data with pandas; drop unused columns (Lat, Long, WHO Region); standardise column names
- Convert Date to datetime
- Handle missing regional values (Province/State) with scikit-learn SimpleImputer
- Aggregate Confirmed, Deaths, Recovered by country and date (groupby)
- Plot trends for every country and for the world with Matplotlib

## Tech stack
Python, Jupyter Notebook, pandas, NumPy, scikit-learn, Matplotlib

## Data
covid_19_clean_complete.csv (included as .zip), daily cases per country.
-
