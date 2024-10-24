# Titanic Data Cleaning

## Overview
This project involves basic data cleaning of the Titanic dataset, which includes passengers' information used to predict survival. The goal is to prepare the data for further analysis and modeling.

## Dataset
The dataset used in this project is the Titanic dataset, which contains various features such as passenger demographics, ticket prices, and survival status.

## Steps Performed
1. **Loading the Dataset**
   - Loaded the Titanic dataset from a CSV file.
  
2. **Checking for Missing Values**
   - Identified columns with missing values.

3. **Handling Missing Values**
   - Dropped the `Cabin` column.
   - Filled missing `Age` values with the median.
   - Filled missing `Embarked` values with the mode.

4. **Outlier Detection**
   - Visualized the `Fare` distribution using box plots to identify outliers.

5. **Handling Outliers**
   - Capped outliers in the `Fare` column at the 95th percentile.

6. **Basic Data Exploration**
   - Provided statistical summaries and explored categorical variables.

## Next Steps
- Further analysis and modeling to predict survival on the Titanic.
- Explore data visualizations for better insights.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Titanic-Data-Cleaning.git
