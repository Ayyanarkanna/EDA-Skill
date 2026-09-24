# Ecommerce_Order_Test_Dataset-Data-R

# Data Cleaning and Exploration

## Code

```python
df['Gender'] = df['Gender'].str.capitalize()

display(df.head())
df.dtypes
df.duplicated()
df.isnull()
df.describe()
df.info()
display(df.head())
```

## Description

This code performs basic data cleaning and exploratory data analysis (EDA) on the dataset.

### Operations Performed

1. **Standardize Gender Values**

   * Converts values in the `Gender` column to a consistent format using capitalization.
   * Example: `male` → `Male`, `female` → `Female`.

2. **Display Dataset Preview**

   * Shows the first five rows of the dataset using `head()`.

3. **Check Data Types**

   * Displays the data type of each column.

4. **Identify Duplicate Records**

   * Checks for duplicate rows in the dataset.

5. **Check Missing Values**

   * Identifies null or missing values in each column.

6. **Generate Summary Statistics**

   * Provides statistical information for numerical columns, such as count, mean, standard deviation, minimum, and maximum values.

7. **Display Dataset Information**

   * Shows column names, non-null counts, data types, and memory usage.

8. **Display Updated Dataset Preview**

   * Displays the first five rows again after data cleaning.
