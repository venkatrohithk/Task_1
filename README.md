# Task_1
**Task 1: Data Cleaning and Preprocessing
Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).**

1) Imported pandas library for loading the csv file.
2) Describe the dataset using df.describe()
3) Identify the null values, missing values, NaN, na using df.isnull() or df.isna().sum()
4) If there are max number of null values, suggested to remove the row using df.drop(columns)
5) Fill the na values using mean for numerical data. (You can use median, mode, etc)
6) Fill the na values using forward fill for categorical data. (You can use backward fill, mode, etc)
7) Remove duplicate rows using .drop_duplicates()
8) Standardize text values (df["COUNTRY"].apply(standardize_country))
9) Convert date formats to a consistent type. replace the '/' with '-' then converted the date into single format.
10) Fixed data types using {pd.to_datetime(df['orderdate'],dayfirst=True, errors='coerce')} function.
11) Finally saved the csv file.
