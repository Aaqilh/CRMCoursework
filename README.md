# S&P 500 Stock Segmentation Using RFM
CRM & CM with Business Intelligence (6BUIS017), individual coursework.

- Notebook: open the .ipynb in Google Colab, then Runtime > Run all.
- Data: S&P 500 list scraped from Wikipedia on 2026-11-21; prices from yfinance, 2021-01-01 to 2025-01-01
- Observation date: 2024-12-31. Random seed: 42.
- Cached data: prices_snapshot.csv.gz".
- Environment: Python 3.13.18, pandas 2.2.3, NumPy 2.4.6, scikit-learn 1.6.1, SciPy 1.16.3, Matplotlib 3.10.0, yfinance 0.2.66.
- Outputs: features_all.csv (feature table), cluster_assignments.csv (cluster labels for all four solutions), exclusion_log.csv, cluster_diagnostics.csv, dendrograms.png, cluster_plots.png.
