# S&P 500 Stock Segmentation Using RFM
CRM & CM with Business Intelligence (6BUIS017), individual coursework.

- Notebook: open the .ipynb in Google Colab, then Runtime > Run all.
- Data: S&P 500 list scraped from Wikipedia on 2026-11-21; prices from yfinance, 2021-01-01 to 2025-01-01 (end exclusive).
- Observation date: 2024-12-31. Random seed: 42.
- Cached data (use if the live download fails): [raw_prices.pkl](https://drive.google.com/file/d/1FMtakKlbOJFtQMDVUl4CwvNhsyRNoq3r/view?usp=sharing). Download it and load with pd.read_pickle("raw_prices.pkl"). It is hosted on Google Drive because it exceeds GitHub's upload limit.
- Environment: Python 3.13.18, pandas 2.2.3, NumPy 2.4.6, scikit-learn 1.6.1, SciPy 1.16.3, Matplotlib 3.10.0, yfinance 0.2.66.
- Outputs: features_all.csv (feature table), cluster_assignments.csv (cluster labels for all four solutions), exclusion_log.csv, cluster_diagnostics.csv, dendrograms.png, cluster_plots.png.
