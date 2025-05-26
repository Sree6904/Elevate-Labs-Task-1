# Elevate-Labs-Task-1
# Titanic Dataset Preprocessing

This repository contains the data cleaning and preprocessing steps for the Titanic dataset.

## Steps Performed

1. **Data Loading**: Loaded the Titanic dataset from CSV
2. **Missing Value Handling**:
   - Age: Filled with median grouped by Pclass and Sex
   - Cabin: Dropped due to high missingness
   - Embarked: Filled with mode
3. **Feature Engineering**:
   - Created FamilySize and IsAlone features
   - Extracted titles from names
4. **Categorical Encoding**:
   - Label encoding for Sex and Embarked
   - One-hot encoding for Title
5. **Numerical Feature Processing**:
   - Log transform for Fare
   - Binning for Age
6. **Outlier Detection and Removal**:
   - Visualized with boxplots
   - Removed Fare outliers using IQR method
7. **Feature Scaling**:
   - Standardized numerical features
   - Normalized Age bins

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
