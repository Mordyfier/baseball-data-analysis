# CISC. 3225 - Data Tool and Algorithms
## Data Analysis Project

This data analysis project aims to analyze and draw conclusions from the [Moneyball](https://www.kaggle.com/wduckett/moneyball-mlb-stats-19622012) dataset on Kaggle.
While the primary designation of the Kaggle dataset is *Moneyball* inspired analysis, this dataset can be used to examine many other questions regarding baseball offensive statistics.

The project utilizes Python. The dataset is placed into a Pandas DataFrame for manipulation and analysis, whereas the visualization work is performed using the Matplotlib and Seaborn packages.

## 1. [Getting the Data - Loading and Cleaning of the Dataset](https://github.com/Mordyfier/baseball-data-analysis/blob/master/1-get-data.ipynb)

This Jupyter Notebook contains the first step in any data analysis - sourcing and entering a dataset into a dataframe. Since this dataset is pretty much clean for our purposes (no null values, except for where warranted and in a way that does not disturb our analysis), the primary work done in this notebook is re-typing variables and reorganizing the columns in a way that will make further analysis easier. The result is then exported to the updated .csv file - baseball_updated.csv.

## 2. [Ethical Audit](https://github.com/Mordyfier/baseball-data-analysis/blob/master/2-ethical-audit.md)

Exploration of ethical ramifications of our analysis: the handling of demographics, missing data, how the data will be used, and sourcing.

## 3. [Variable Description](https://github.com/Mordyfier/baseball-data-analysis/blob/master/3-variable-description.ipynb)

A deeper dive back into the dataset and the resulting pandas dataframe. Reorganization of default 0-n indices into a more appropriate multi-index ('Year', 'Team'). Description and basic statistical analysis (mean, median, quartiles, outliers, underlying distribution estimation, correlations) of each numeric variable.  

## 4. Higher-Level Analysis

## 5. Final Report
