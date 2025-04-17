# Video Games Sales Report

## Dataset Overview
The dataset contains 16,598 entries and 11 columns. It provides information on video game sales across different regions and platforms.

### Data Source
The data was sourced from a CSV file named `video_games_sales.csv` and is available on Kaggle: [Video Games Sales](https://www.kaggle.com/datasets/zahidmughal2343/video-games-sale).

### Data Structure
- **Rank**: Integer, non-null
- **Name**: Object, non-null
- **Platform**: Object, non-null
- **Year**: Float, some missing values
- **Genre**: Object, non-null
- **Publisher**: Object, some missing values
- **NA_Sales**: Float, non-null
- **EU_Sales**: Float, non-null
- **JP_Sales**: Float, non-null
- **Other_Sales**: Float, non-null
- **Global_Sales**: Float, non-null

### Data Cleaning
- Missing values in the `Year` and `Publisher` columns were handled.
- Outliers were identified and addressed, impacting the dataset by improving the accuracy of the analysis.

## Key Findings
- The dataset shows a wide distribution of sales across different regions, with North America having the highest sales figures.
- Platforms like Wii and NES are among the top in terms of sales.

## Summary Statistics
- The average global sales per game is approximately 0.54 million units.
- The maximum sales recorded for a single game is 82.74 million units.

This report summarizes the key aspects of the dataset and the insights gained from the analysis.