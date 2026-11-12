# Heart Failure Records

An exploratory analysis and regression practice project on a clinical heart failure dataset: 299 patients, with age, ejection fraction, serum creatinine and sodium, comorbidities and follow-up time.

## Repository Contents

| File | Description |
|---|---|
| `heart failure records .ipynb` | Full analysis: EDA and linear regression models |
| `heart failure records.csv` | Heart failure clinical records (299 patients, 13 columns) |

## Commit History

### `256ed70`: Upload of the notebook and dataset (2022-05-18)
- **EDA:**
  - most patients are in their late 50s to early 60s
  - follow-up times cluster between 75 and 90 days
  - ejection fraction is mostly between 35 and 40
- **Count plots:**
  - most patients survived
  - most didn't smoke
  - most didn't have high blood pressure, diabetes or anaemia
- **Simple linear regressions:**
  - serum creatinine vs. serum sodium: no meaningful relationship (R² below 0)
  - age vs. follow-up time: about 3% correlation
  - creatinine phosphokinase vs. platelets: essentially no relationship
- **Multiple linear regression:** predicts a patient's age from the other clinical features (e.g. predicting 63 years for the first row), with evaluation and result plots.

## Tools
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook
