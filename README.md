# Books Data Analysis Project

## Overview

This project involves analyzing a dataset containing information about books, including publishing year, book name, author, language, ratings, sales, and revenue. Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn are used for data manipulation, visualization, and analysis.

## Project Contents

- **Data Import**: The project starts by importing the dataset (`Books_Data_Clean.csv`) into a Pandas DataFrame.
- **Data Cleaning**: Negative publishing years are filtered out, and rows with missing values in the "Book Name" column are dropped.
- **Data Exploration**:
  - Descriptive statistics of the dataset are calculated using the `describe()` method.
  - Missing values are identified using the `isna().sum()` method.
  - Duplicates are checked using the `duplicated().sum()` method.
  - Unique values in each column are counted using the `nunique()` method.
- **Data Visualization**:
  - Histogram: Distribution of publishing years.
  - Bar Chart: Number of books in each genre.
  - Box Plot: Book ratings count for each genre.
  - Scatter Plot: Relationship between sale price and units sold.
  - Pie Chart: Language distribution of books.
  - Bar Chart: Total publisher revenue for each publisher.
  - Box Plot: Units sold for each author rating.
  - Line Plot: Total units sold over the years.
- **Insights**:
  - Top authors based on average book rating.
  - Distribution of books by language code.
  - Maximum book ratings count for each author rating.
  - Total gross sales for top 20 authors.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Usage

1. Ensure you have Python installed on your system.
2. Install the required libraries using `pip install pandas numpy matplotlib seaborn`.
3. Clone this repository or download the `Books_Data_Clean.csv` file.
4. Run the Python script in your preferred environment (e.g., Jupyter Notebook) to execute the analysis and visualize the data.

