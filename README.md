# Covid-19_Data_Analyst_SQL
I developed a comprehensive project in Excel, creating multiple dashboards and tables to analyze the data. This process involved several stages, including data preprocessing, data cleaning, and data visualization.

This repository presents a comprehensive data analysis project focused on understanding the impact and trends of the COVID-19 pandemic using SQL. The analysis covers various aspects, including infection rates, mortality rates, and vaccination progress across different geographical regions.

## Project Overview

The primary goal of this project is to extract meaningful insights from raw COVID-19 datasets using SQL queries. It aims to provide a clear picture of the pandemic's evolution, identify key affected areas, and track vaccination efforts. The analysis is designed to be easily reproducible and extensible for further research or visualization.

## Data Sources

The analysis relies on two main datasets, typically structured as SQL tables:

1.  **`coviddeaths`**: Contains daily or periodic records of COVID-19 cases, deaths, population figures, and geographical information.
2.  **`covidvaccinations`**: Provides data on new vaccinations administered, linked by location and date to the `coviddeaths` table.

*(Note: The actual data files are not included in this repository due to their dynamic nature and potential size. Users are expected to source similar datasets or populate these tables with their own data.)*

## Analysis Highlights

The `sql` directory contains a series of SQL queries that perform the following analyses:

*   **Mortality Rate Calculation**: Analyzing the percentage of deaths relative to total cases.
*   **Infection Rate Calculation**: Determining the percentage of the population infected.
*   **Geographical Impact**: Identifying countries and continents with the highest infection and death counts.
*   **Global Trends**: Aggregating data to understand worldwide COVID-19 statistics.
*   **Vaccination Progress**: Tracking the rolling count of vaccinated individuals and the percentage of the population vaccinated over time.
