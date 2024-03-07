# Population, Fertility, and Life Expectancy Analysis

## Overview

This Python script combines data from various sources, including country metadata, fertility rates, population statistics, and life expectancy data. It preprocesses the data and utilizes Plotly Express to create interactive visualizations, providing insights into the relationships between population, fertility rates, and life expectancy across different regions and countries.

## Data Sources

1. **Country Metadata:** The script reads metadata about countries from the "Metadata_Country.csv" file.

2. **Fertility Rates:** Fertility rate data is loaded from the "fertility_rate.csv" file.

3. **Population Statistics:** Population data is obtained from the "country_population.csv" file.

4. **Life Expectancy Data:** Life expectancy information is retrieved from the "life_expectancy.csv" file.

## Data Preprocessing

The script defines a function (`preprocess_df`) for preprocessing each DataFrame. It removes unnecessary columns, handles missing values, and transforms the data into a format suitable for analysis.

## Merging DataFrames

The script merges the processed DataFrames based on the 'Country Code' and 'Year' columns. It combines information about life expectancy, fertility rates, and population in a unified DataFrame for analysis.

## Data Analysis and Visualization

### Animated Scatter Plot

A scatter plot is generated using Plotly Express, illustrating the relationship between fertility rates and life expectancy. The size of markers represents population, and the animation is based on years. The plot is color-coded by region, providing a dynamic view of trends over time.

### Animated Bar Chart

An animated bar chart is created to visualize the population of different regions over the years. The bars represent each country within a region, and the animation adds a temporal dimension to the analysis.

### Population Over Time

A line chart is generated to depict the population trends over the years. Each country is represented by a unique line, allowing for a detailed view of population changes over time.

### Histograms

Two histograms are plotted, one for life expectancy and another for fertility rates. These visualizations provide insights into the distribution of life expectancy and fertility across the dataset.

## Usage

- Ensure the required libraries (Pandas, NumPy, and Plotly Express) are installed.
- Download the provided dataset files: "Metadata_Country.csv," "fertility_rate.csv," "country_population.csv," and "life_expectancy.csv."
- Adjust the file paths in the script to match the location of your dataset files.
- Run the script to perform data preprocessing, merge datasets, and generate interactive visualizations.

