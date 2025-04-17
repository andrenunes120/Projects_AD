# Air Quality Index (AQI) Data Analysis Project

## Dataset Source

The dataset was sourced from Kaggle: [AQI (Air Quality Index)](https://www.kaggle.com/datasets/azminetoushikwasi/aqi-air-quality-index-scheduled-daily-update)

## Dataset Structure and Initial Exploration

The dataset contains 18,759 records and 4 columns: Date, Country, Status, and AQI Value. Initial exploration confirmed the structure and provided summary statistics for each column.

## Missing Values

There are no missing values in any column. This was verified both by checking for missing entries and by calculating the percentage of missing values, which was 0% for all columns.

## Outlier Detection and Removal

Outliers in the 'AQI Value' column were identified using the interquartile range (IQR) method. Values outside the lower and upper bounds were considered outliers and removed. After this process, the dataset size was reduced from 18,759 to 18,103 records.


## Impact of Data Cleaning

The removal of outliers resulted in a cleaner dataset, with more reliable AQI values for subsequent analysis. The summary statistics and box plots after cleaning confirmed the improved data quality.