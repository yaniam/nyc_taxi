NYC Taxi Notebook
=================

This project contains a single notebook, `nyc_taxi.ipynb`, that explores a
sample of New York City yellow taxi trips. It loads the raw CSV data, combines
it with the helper labels in `combined_labels.json`, and walks through quick
checks such as distributions, cleaning steps, and a lightweight model sketch.

Working with the project
------------------------

1. Create a Conda environment with `environment.yml` (or install the listed
   packages manually).
2. Open the notebook in Jupyter or VS Code and run the cells top to bottom.
3. Keep `nyc_taxi.csv` in the repo root so the notebook can find it without
   editing paths.

Future ideas
------------

- Expand the feature engineering section (time of day, route clusters, etc.).
- Try a proper train/test split and track the metrics.
- Push visualizations or summary tables to a small dashboard once results look
  stable.

