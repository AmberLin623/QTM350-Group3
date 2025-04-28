# QTM350-Group3
## Project Description
Early Life Matters: Shifting Impacts of Under-5 Mortality and Adolescent Fertility on Life Expectancy, 1960s–2020s

This project investigates how early-life health indicators—specifically under-5 mortality rates and adolescent fertility rates—affect life expectancy at birth, and how these relationships have evolved globally from the 1960s to the 2020s. We analyzed trends across different income groups using World Bank datasets and a merged, cleaned panel dataset of over 11,536 observations.

## Key Findings
1. Reducing under-5 mortality consistently improves life expectancy across all countries.
2. Adolescent fertility has a weaker, more variable impact depending on a country’s economic context.

The analysis included descriptive statistics, regression modeling with standardized coefficients, and visualizations such as scatter plots and decade-based comparisons. Our results emphasize the critical importance of early-life public health interventions in improving population longevity and promoting global health equity.

## Instructions on Running the Code
### Data Folder 
The first three CSV files are the original datasets from the World Bank's API, and population_panel_clean.csv is the cleaned dataset we used in our analysis. 

### Scripts Folder 
This folder contains all the SQL and Python scripts we used in this project. The analysis.ipynb document contains codes for all the correlational analyses between three indicators and in terms of different income groups. In data_clean.ipynb, you can see how the group merged and cleaned the three original datasets. The des_stats.ipynb document includes descriptive analysis and illustrations about data distributions. 

### Documentation Folder 
Here is our final output of the project. You may view it in HTML or PDF form. 

### Figures Folder 
All the plots and graphic illustrations are included in this folder for presentation. 

## Detailed Steps to Explore 
1. Clone the Repository
```bash
git clone https://github.com/AmberLin623/QTM350-Group3.git
cd QTM350-Group3
```
2. Make sure you have Python 3 installed. Then install the necessary packages:
```bash
pip install pandas matplotlib seaborn scikit-learn
```
3. Explore the Scripts

data_clean.ipynb — Data cleaning and preprocessing.

des_stats.ipynb — Descriptive statistics and basic data exploration.

analysis.ipynb — Regression analysis and visualizations.

Qtm 350-Group Project.ipynb — Combined final report notebook.

4. View Figures
All plots generated during the analysis are saved in the figures/ folder. You can also regenerate them by rerunning the Jupyter notebooks.

Tip: Run all cells sequentially to fully reproduce the analysis.
