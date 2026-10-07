# Data Analysis Projects

A collection of exploratory data analysis and machine learning projects, primarily developed in Jupyter notebooks. The repository includes work with sales, sports, soil grain size, and Kaggle datasets.

## Projects

- **Sales data** — analysis of monthly 2019 sales data in `Sales_Data/sales.ipynb`. The folder also includes the monthly CSV files and a combined dataset.
- **Soil grain size distribution** — notebook exploration and prediction work in `Kaggle soil grain size distribution.ipynb` and `Soil_Grain_size_Dist/`. Supporting CSV data is stored alongside the project.
- **Electric vehicle purchases** — Kaggle prediction project with train, test, and submission CSV files in `Predicting Electric Vehicle Purchases Kaggle comp/`; related notebooks are in the repository root.
- **Tennis** — analysis notebook `tennis.ipynb` and ATP data in `Tennis Data/`.
- **Additional modeling experiments** — `s6e9-single-xgb-cv-0-94488.ipynb` and saved prediction arrays (`oof_preds_base.npy`, `test_preds_base.npy`).


## Repository notes

- Keep each analysis close to its source data where practical.
- Large or generated artifacts, including prediction arrays and plots, are supporting outputs for the associated analyses.
- `main.py` is a small Python entry point and currently prints a greeting; the analyses are maintained in the notebooks.
