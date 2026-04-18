
# Project Title

A brief description of what this project does and who it's for

# Netflix Data Cleaning Project 🎬

## Project Overview
This project focuses on cleaning and preprocessing the **Netflix Movies and TV Shows** dataset. Raw data often contains missing values, duplicates, and inconsistent formatting. This project aims to resolve these issues to ensure the data is ready for accurate analysis and visualization.

## Dataset Description
The dataset used is `netflix1.csv`, which contains information about movies and TV shows available on Netflix, including:
* **Show ID:** Unique identifier for each show.
* **Type:** Movie or TV Show.
* **Title:** Name of the content.
* **Director:** Content director (contains missing values).
* **Country:** Production country.
* **Release Year:** Original release year.
* **Rating:** Content rating (e.g., PG-13, TV-MA).
* **Duration:** Runtime in minutes or seasons.
* **Listed In:** Categories/Genres.

## Cleaning Steps Performed
In this project, I performed the following data cleaning tasks:
1. **Handling Missing Values:** Addressed null values in columns like `Director` and `Country` by filling them with 'Not Given' or using appropriate imputation.
2. **Data Consistency:** Standardized date formats and text columns.
3. **Removing Duplicates:** Identified and removed any duplicate entries to maintain data integrity.
4. **Data Type Conversion:** Corrected data types for columns (e.g., converting dates to datetime objects).
5. **Outlier Detection:** Checked for any inconsistencies in release years and durations.

## Tools Used
* **Python** 
* **Pandas:** For data manipulation and cleaning.
* **Jupyter Notebook:** For interactive development and documentation.

