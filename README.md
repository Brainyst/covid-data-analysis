# COVID-19 Data Analysis Project

This project provides an analysis of COVID-19 data, including data cleaning, data aggregation, and visualizations. The dataset used is sourced from an open dataset on COVID-19 cases worldwide, which is loaded directly from a GitHub URL. The analysis covers various metrics such as total cases, total deaths, GDP per capita, and human development index, aggregated by continent. 

## Dataset

The dataset is sourced from [COVID-19 Data on GitHub](https://github.com/SR1608/Datasets/main/covid-data.csv). The data includes information on COVID-19 cases, deaths, GDP per capita, and human development index for different locations and continents.

## Project Structure

The analysis is organized into the following sections:

1. **High-Level Data Understanding**: Overview of dataset structure, column data types, and summary statistics.
2. **Low-Level Data Understanding**: Exploration of specific columns, including unique values and quartiles.
3. **Data Cleaning**: Removing duplicates, handling missing values, and filtering relevant columns.
4. **Data Transformation**: Date formatting and feature engineering, such as creating a new month column.
5. **Data Aggregation**: Grouping data by continent for further analysis.
6. **Feature Engineering**: Calculating the `total_deaths_to_total_cases` ratio.
7. **Data Visualization**: Visualizations of GDP per capita distribution, total cases vs. GDP, and total cases by continent.

## Requirements
The project requires Python 3.x and the following Python libraries (listed in requirements.txt):

• pandas<br>
• numpy<br>
• matplotlib<br>
• seaborn <br>

## Usage

1. Run the covid_data_analysis.py script:

➤ python covid_data_analysis.py

2. The script will generate various data visualizations and save the grouped data as df_groupby.csv.
   
## Output

The df_groupby.csv file includes the aggregated COVID-19 data by continent, along with the calculated total_deaths_to_total_cases feature.
