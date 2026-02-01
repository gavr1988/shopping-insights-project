# Projectone

Sales data analysis and visualization using Jupyter notebooks. The workflow loads three source datasets, cleans and merges them, engineers features, and explores sales patterns by store type, holidays, markdowns, and weather. A Tableau workbook is included for dashboarding.

## Contents
- Notebooks
	- analysis.ipynb: end-to-end analysis and visualizations.
	- data_cleaning.ipynb: data loading and cleaning utilities.
- Data
	- DATA/sales data-set.csv
	- DATA/stores data-set.csv
	- DATA/Features data set.csv
	- DATA/cleaned_merged_data.csv
	- DATA/cleaned_merged_data_v2.csv
- Tableau
	- tableau projectone.twb

## How to run
1. Open analysis.ipynb.
2. Run the first cell to execute data_cleaning.ipynb and load datasets.
3. Run remaining cells to reproduce cleaning, feature engineering, and analysis.

## Outputs
- Cleaned and merged dataset: DATA/cleaned_merged_data.csv
- Updated export: DATA/cleaned_merged_data_v2.csv

## Key analyses
- Total sales by store type
- Holiday vs non-holiday sales
- Markdown effectiveness (correlations)
- Weather impact on sales (temperature ranges)

## Requirements
- Python with pandas, numpy, matplotlib, seaborn, plotly
