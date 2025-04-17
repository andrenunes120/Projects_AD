# Students Performance Dataset Analysis

## Dataset Overview
This analysis is based on the [Students Performance in Exams dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) from Kaggle. The dataset contains information about student demographics and their performance in math, reading, and writing tests.

## Dataset Characteristics
- **Total Records**: 1000 students
- **Features**: 8 columns including demographic and academic performance data
- **Gender Distribution**: 518 females, 482 males

## Data Features
1. **Demographic Information**:
   - Gender
   - Race/ethnicity (Groups A-E)
   - Parental level of education
   - Lunch type (standard or free/reduced)
   - Test preparation course completion status

2. **Performance Metrics**:
   - Math Score
   - Reading Score
   - Writing Score

## Key Findings

### Score Statistics
- **Math**: Mean = 66.09, Std = 15.16
- **Reading**: Mean = 69.17, Std = 14.60
- **Writing**: Mean = 68.05, Std = 15.20

### Gender Performance Analysis
- **Females**:
  - Math: 63.63
  - Reading: 72.61
  - Writing: 72.47

- **Males**:
  - Math: 68.73
  - Reading: 65.47
  - Writing: 63.31

### Correlation Analysis
Strong positive correlations between test scores:
- Reading and Writing: 0.95
- Math and Reading: 0.82
- Math and Writing: 0.80

## Data Quality
- Complete dataset with no missing values
- Score ranges: 0-100 for all tests
- Well-structured categorical variables
- Balanced gender distribution

## Methodology
1. Initial data exploration and quality assessment
2. Descriptive statistical analysis
3. Correlation analysis between performance metrics
4. Gender-based performance comparison
5. Visualization of key relationships

## Source Attribution
Data sourced from Kaggle: [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)