# Air Quality Index (AQI) Data Analysis Project

## Dataset Source
The dataset was sourced from Kaggle: [AQI (Air Quality Index) Scheduled Daily Update](https://www.kaggle.com/datasets/azminetoushikwasi/aqi-air-quality-index-scheduled-daily-update)

## Dataset Characteristics
- **Total Records**: 18,759 entries
- **Columns**: 
  - Date
  - Country
  - Status
  - AQI Value

## Data Quality Assessment

### Missing Values
- No missing values were found in any of the columns
- All columns (Date, Country, Status, AQI Value) contain complete data

### Outlier Analysis
- **Number of Outliers**: 656 records identified
- **Detection Method**: Interquartile Range (IQR) method
- **Sample Outliers**:
  - Bahrain: AQI Value 165
  - Chile: AQI Value 178
  - Ethiopia: AQI Value 165
  - Iran: AQI Value 250
  - Iraq: AQI Value 234

## Data Transformation

### Log Transformation
- Applied log transformation to AQI Values to handle skewness
- Original Data Statistics:
  - Mean: 63.74
  - Standard Deviation: 50.29
  - Range: 1 to 963
- Transformed Data Statistics:
  - Mean: 3.89
  - Standard Deviation: 0.81
  - Range: 0.69 to 6.87

### Data Files
- Original data: `data_date.csv`
- Transformed data: `data_transformed.csv`

The transformation significantly improved the data distribution, making it more suitable for statistical analysis and modeling.