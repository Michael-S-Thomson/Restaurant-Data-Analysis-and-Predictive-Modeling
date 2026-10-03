# Level 2 - Task 3: Feature Engineering

## Objective

Create additional features from the restaurant dataset to improve data
analysis and prepare the dataset for further machine learning tasks.

## Features Created

The following features were created:

1. **Restaurant Name Length**
   - Calculates the number of characters in the restaurant name.

2. **Address Length**
   - Calculates the number of characters in the restaurant address.

3. **Has Table Booking Encoded**
   - Converts table booking availability into numerical values:
     - Yes = 1
     - No = 0

4. **Has Online Delivery Encoded**
   - Converts online delivery availability into numerical values:
     - Yes = 1
     - No = 0

## Dataset Summary

- Original rows: 9,551
- Original columns: 21
- Final columns: 25
- Missing values after feature engineering: 0
- Duplicate rows: 0

## Tools and Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Output

The feature-engineered dataset was saved as:

`Feature_Engineered_Dataset.csv`

## Conclusion

Feature engineering added four useful numerical features to the restaurant
dataset. These features can be used for further analysis and machine learning
tasks.