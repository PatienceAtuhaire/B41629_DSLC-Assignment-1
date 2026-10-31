# Data Science Lifecycle — Assignment One

**Student:** Atuhaire  
**Course:** MSc Data Science, Data Science Lifecycle  
**Submission archive:** `Assignment1_Atuhaire.zip`

## Deliverables

- `Assignment1_Atuhaire.ipynb` — executed notebook answering all five assignment questions.
- `Atuhaire_Data.csv` — cleaned dataset produced by the notebook.
- `README.md` — this guide.

The notebook uses `automobileEDA.csv` as its input. Keep that file in the same folder as the
notebook to rerun the analysis.

## Run the notebook

The notebook uses Python with pandas, NumPy, scikit-learn, SciPy, Plotly, statsmodels,
scikit-posthocs, SHAP, and Jupyter. Open the notebook in Jupyter or VS Code and run its cells
from top to bottom. Interactive charts are embedded in the notebook.

## Notes

- The cleaned CSV contains 201 rows and has no missing values or exact duplicate rows.
- Multivariate outliers are reviewed individually; plausible luxury, diesel, and uncommon cars
  are retained.
- Model validation is exploratory: the consensus feature subset is selected before the
  cross-validation comparison, which may make the reported scores optimistic.
