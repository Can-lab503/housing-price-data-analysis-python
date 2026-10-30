# Housing Price Data Analysis with Python

## What this is
A Python data analysis pipeline on a 2,000-row housing dataset, covering missing-value handling, outlier detection, correlation analysis, and feature preparation for downstream modelling.

## Data

- **File**: `house_train` (included in this repository, ~326 KB)
- **Rows**: 2,000
- **Source**: Originally obtained from a public Kaggle dataset. The original dataset page is no longer accessible, so the raw file is included here for reproducibility.

## What I did
- Cleaned missing values and implemented a reusable outlier-processing function based on Pearson normality tests with 3σ/IQR thresholds.
- Performed correlation analysis (Matplotlib/Seaborn) to identify area, crime rate, and PM2.5 as the top price-correlated features.
- Applied Z-score standardization and equal-width binning to price for downstream analysis.

## Tools
Python (pandas, numpy, scipy, scikit-learn, matplotlib, seaborn)
