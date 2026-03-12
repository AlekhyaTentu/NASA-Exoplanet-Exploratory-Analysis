# NASA Exoplanet Data Analysis

Exploratory data analysis and predictive modeling on NASA's exoplanet 
dataset, examining planetary characteristics, habitability indicators, 
and discovery patterns across confirmed exoplanets.

## What This Project Does

Raw NASA exoplanet data is messy. Inconsistent entries, missing values, 
and columns that need engineering before they mean anything. This project 
handles all of that — cleaning, transforming, and analyzing the dataset 
to surface patterns that are actually meaningful.

## Key Analysis Areas

- Planetary size and orbital period distributions across discovery methods
- Habitability zone analysis based on stellar and planetary parameters  
- Feature correlation analysis to identify the strongest predictors 
  of planetary classification
- Visual exploration of discovery trends over time across telescopes 
  and missions

## Tech Stack

- **Python** — Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook** — end-to-end analysis and visualization
- **Dataset** — NASA Exoplanet Archive (cleaned version included)

## Files

| File | Description |
|------|-------------|
| `main_notebook.ipynb` | Full analysis, visualizations, and findings |
| `nasa_exoplanets.csv` | Original dataset from NASA Exoplanet Archive |
| `cleaned_exoplanets.csv` | Preprocessed and feature-engineered dataset |
| `601 report.pdf` | Final project report — UMBC DATA 601 |

## How to Run
```bash
git clone https://github.com/AlekhyaTentu/Datascience_Masters_Project
cd Datascience_Masters_Project
jupyter notebook main_notebook.ipynb
```

---
*University of Maryland Baltimore County — DATA 601: Introduction to Data Science*
```

---

**Also add this as the repo About description** (the one-liner that shows on your profile):
```
Exploratory data analysis and predictive modeling on NASA's exoplanet 
dataset using Python, Pandas, and Jupyter. UMBC DATA 601 capstone.
