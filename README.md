# Covid-19 Data Exploration

This project involves exploring and analyzing Covid-19 data using SQL. It includes various queries to analyze total cases, total deaths, infection rates, death rates, and vaccination rates across different countries and continents.

## Skills Used

- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Creating Views
- Converting Data Types

## Data Sources

The project uses two main datasets:
1. `CovidDeaths`
2. `CovidVaccinations`

## Queries Included

1. **Basic Data Selection**
   - Selecting all records where the continent is not null.
   - Ordering records based on specific columns.

2. **Total Cases vs. Total Deaths**
   - Analyzing the likelihood of dying if infected by Covid-19 in various countries.

3. **Total Cases vs. Population**
   - Calculating the percentage of the population infected with Covid-19.

4. **Highest Infection Rates**
   - Identifying countries with the highest infection rates compared to their populations.

5. **Highest Death Counts**
   - Finding countries with the highest death counts per population.

6. **Continent-wise Analysis**
   - Showing continents with the highest death counts per population.

7. **Global Numbers**
   - Aggregating global Covid-19 statistics.

8. **Vaccination Analysis**
   - Using window functions, CTEs, and temporary tables to analyze the percentage of the population vaccinated.

9. **Creating Views**
   - Creating views to store data for later visualizations.

## Contribution

Feel free to fork this repository, make changes, and create a pull request if you have any improvements or suggestions.

## License

This project is open-source and available under the [MIT License](LICENSE).

