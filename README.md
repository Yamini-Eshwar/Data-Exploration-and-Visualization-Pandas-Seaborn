# Country Statistics: Birth Rate vs Internet Users Analysis

This repository contains the analysis of a dataset that provides information about various countries, including their birth rates, internet usage percentages, and income groups. The dataset is explored using **pandas** for data manipulation and **seaborn** and **matplotlib** for data visualization.

## Key Operations and Visualizations

### 1. **Data Exploration**
   - **Read and Load Data**: The dataset is loaded into a pandas DataFrame.
   - **Data Inspection**: Checked the structure and summary statistics of the dataset.
   - **Column Renaming**: Renamed columns to more meaningful names (e.g., `CountryName`, `CountryCode`, `BirthRate`, `IncomeGroup`).
   - **Data Filtering**: Filtered countries with a `BirthRate` greater than 40 and other conditions.

### 2. **Data Visualizations**
   - **Distribution Plot**: Used `sns.histplot()` to visualize the distribution of internet usage across countries with a Kernel Density Estimation (KDE).
   - **Box Plot**: Visualized the spread and outliers of `BirthRate` for different income groups using `sns.boxplot()`.
   - **Linear Model Plot**: Showed the relationship between `InternetUsers` and `BirthRate` across income groups using `sns.lmplot()`.

