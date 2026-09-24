# Data Preprocessing

## Data Exploration

1. The unique values and the number of unique values for each feature is identified.
2. Statistical analysis of the columns is performed.
3. The columns are renamed.

## Data Cleaning
1. The inappropriate values in the company column has been corrected.
2. The duplicate rows are removed.
3. No outlier have been identified.
4. The missing values in categorical columns are filled with the mode values of the respective columns and the missing values in the numerical columns are filled with the mean values of the respective columns.

## Data Analysis
1. The data is filtered with the condition age > 40 and salary < 5000.
2. Scatter plot is plotted for age and salary.
3. The number of people from each place is calculated and the same is visualized using a bar chart.

## Data Encoding
1. Except for country column, label encoding is used for all the other columns as one-hot encoding may result in an increase in the number of features.

## Feature Scaling
1. Both StandardScaler and MinMaxScaler is applied to the cleaned data.