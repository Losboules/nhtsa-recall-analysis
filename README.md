# NHTSA Recall Analysis | Automotive Data Science

An end-to-end data science project analyzing U.S. vehicle and equipment recall campaigns from 2013–2022.

## Overview
This project explores recall frequency, manufacturer-level patterns, campaign size, and forecasting using publicly available NHTSA recall data.

## Technologies
- Python
- pandas and NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Key Findings
- The largest 10% of campaigns accounted for approximately 77.5% of vehicle and 80.6% of equipment affected units in the analyzed data.
- Recall frequency and affected population reveal different manufacturer-level patterns.
- A historical-mean baseline was preferred over Ridge regression for the evaluated forecasting task.

## Methodology
1. Import and clean NHTSA recall records.
2. Deduplicate records by campaign number.
3. Normalize manufacturer and brand mappings.
4. Analyze recall frequency and affected populations.
5. Evaluate campaign-size concentration.
6. Compare forecasting approaches against a baseline.

## Data
Source: National Highway Traffic Safety Administration (NHTSA).

Download the relevant public recall datasets from NHTSA and place FLAT_RCL.txt and RCL.txt inside the data/ directory.

## Run the Analysis
Open RECALL_ANALYSIS.ipynb in Jupyter Notebook or VS Code. Install the Python libraries used in the notebook and run the cells in order.

## Notes
This is an independent portfolio analysis. Findings are based on the selected data, filters, and methodology rather than the full universe of U.S. recalls.
