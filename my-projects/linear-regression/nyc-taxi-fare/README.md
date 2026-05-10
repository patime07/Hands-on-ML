# NYC Yellow Taxi Fare — Linear Regression

Linear regression predicting `fare_amount` from `trip_distance` on NYC TLC Yellow Taxi trip records (January 2026, 3.7M rows).

## Dataset

- Kaggle: [Link to csv](https://www.kaggle.com/datasets/fatimazahraiguenfer/nyc-tlc-yellow-taxi-trip-2026)
- Original source: [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

Download `yellow_tripdata_2026-01.parquet` into `data/` before running.

## Pipeline

1. **Load**
2. **EDA**
3. **Handle missing values** 
4. **Understanding Correlation**
5. **Outlier detection and Data cleaning**
6. **Feature selection** 
7. **Train/test**

## Results

| Set   | R²     |
|-------|--------|
| Train | 76.66% |
| Test  | 76.38% |


## Requirements
```
numpy pandas matplotlib seaborn scikit-learn pyarrow
```
