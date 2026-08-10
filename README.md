# Karnataka Agricultural Data Analysis

## Project Overview

This project presents a data analysis of the Karnataka Agricultural Dataset using Python. The main objective is to understand the structure and characteristics of the dataset, identify and address data quality issues, and uncover meaningful patterns through statistical analysis and data visualization.

## Dataset
The dataset used in this project was provided as part of my Machine Learning course with [Mohamadreza Momeni](https://github.com/MrezaMomeni).

### Dataset Source
The dataset is also available on Kaggle:
[Agriculture dataset | Karnataka]
(https://www.kaggle.com/datasets/imtkaggleteam/agriculture-dataset-karnataka)
The dataset is attributed on Kaggle to Rajesh Naik and is published under the CC BY 4.0 license.

This project was completed for educational and portfolio purposes.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Missingno

## Data Cleaning

The following data quality issues were investigated and addressed:

* Missing values
* Duplicate records (none found)
* Inconsistent data types
* Inconsistent categorical values and typographical errors
* Potential outliers in rainfall and price
* A temperature data-entry issue caused by inconsistent value scales

The dataset initially contained 74 rows with missing values out of 3,158 rows. These rows were removed because they represented a relatively small portion of the dataset.

## Exploratory Data Analysis

The analysis includes:

* Rainfall comparison across locations
* Temperature comparison across locations
* Price distribution
* Average price comparison across crop types
* Correlation analysis using heatmaps
* Crop-specific correlation analysis
* Relationship between rainfall and temperature
* Crop observations across different years

## Key Findings

* Rainfall values vary considerably across locations.
* The price distribution contains two distinct ranges of values.
* Average prices differ considerably across crop types, with Paddy showing the highest average price and Blackgram the lowest among the analyzed crops.
* The overall correlation matrix shows mostly weak linear relationships between numerical variables.
* Crop-specific analysis reveals stronger relationships for some individual crop groups, such as the relationship between Area and Yields for Cotton.
* The number of recorded crop observations varies considerably across years, with a particularly high number of records in 2004.

## Project Structure

```text
Karnataka-Agricultural-data-analysis/
│
├── Karnataka-Agricultural-data-analysis.ipynb
├── karnataka.csv
└── README.md
```

## Conclusion

This project provided practical experience in data cleaning, exploratory data analysis, data visualization, and interpreting patterns in a real-world agricultural dataset.

